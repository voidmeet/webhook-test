pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout code from GitHub
                checkout scm
            }
        }

        stage('Build') {
            steps {
                // Simulate build process
                echo 'Building...abcd again'
            }
        }

        stage('Test') {
            steps {
                // Simulate testing
                echo 'Testing...best again'
            }
        }

        stage('Deploy') {
            steps {
                // Simulate deployment
                echo 'Deploying...stage again'
            }
        }
    }
}
