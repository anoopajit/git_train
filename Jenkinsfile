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
                // Add your build commands here
                sh 'echo "Building"'
            }
        }

        stage('Test') {
            steps {
                // Add your test commands here
                sh 'echo "Testing"'
            }
        }
    }
}
