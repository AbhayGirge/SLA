pipeline {
    agent any 
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out code from GitHub...'
            }
        }
        stage('Build') {
            steps {
                echo 'Compiling code...'
                sh 'ls -l'
            }
        }
        stage('Test') {
            steps {
                echo 'Running Unit Tests...'
            }
        }
    }
}
