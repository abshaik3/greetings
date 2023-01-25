#!groovy
pipeline {
    agent any
    stages {
        stage('Build') {
            environment {
                DEV_COMMON_CREDS = credentials('055ef619-9b6e-4f08-9a8a-e4caa00e6faa')
            }

            steps {
                echo 'Building..'
                echo 'DEV_COMMON_CREDS_USR = $DEV_COMMON_CREDS_USR'
                echo 'DEV_COMMON_CREDS_PSW = $DEV_COMMON_CREDS_PSW'
            }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
