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
                echo 'Building...dev branch again'
            }
        }

        stage('Test') {
            steps {
                // Simulate testing
                echo 'Testing...dev branch again'
            }
        }

        stage('Deploy') {
            steps {
                // Simulate deployment
                echo 'Deploying...dev branch again'
            }
        }
    }
}
