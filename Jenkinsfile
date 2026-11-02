pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Getting project files'
            }
        }

        stage('Docker Version') {
            steps {
                sh 'docker --version'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t my-devops-app .'
            }
        }

        stage('Run Container') {
            steps {
                sh 'docker run -d --name jenkins-app -p 8082:80 my-devops-app'
            }
        }

        stage('Success') {
            steps {
                echo 'Docker deployment completed!'
            }
        }
    }
}