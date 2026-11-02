pipeline {
    agent any

    stages {

<<<<<<< HEAD
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
=======
        stage('Welcome') {
            steps {
                echo 'Welcome to Jenkins!'
            }
        }

        stage('Install') {
            steps {
                echo 'Installing application'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application'
            }
        }

        stage('Test') {
            steps {
                echo 'Application testing'
>>>>>>> 74e42a8fad3a19401def3c884588ccfa8fa52644
            }
        }
    }
}