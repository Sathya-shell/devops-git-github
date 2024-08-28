pipeline {
    agent any 

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // Commands to build the project
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Commands to test the project
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Commands to deploy the project
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded!'
        }
        failure {
            echo 'Pipeline failed.'
        }
    }
}

