pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                bat 'echo Hello from Jenkins'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'dir'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the app...'
            }
        }
    }

    post {
        success { echo 'Pipeline finished successfully!' }
        failure { echo 'Pipeline failed.' }
    }
}
