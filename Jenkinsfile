pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out repository'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'echo "Building..."'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "Running tests..."'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                sh 'echo "Deploying..."'
            }
        }
    }
}
