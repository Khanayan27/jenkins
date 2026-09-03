pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Compiling the code..."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying to server..."'
            }
        }
        stage('Cleanup'){
            steps {
                sh 'echo "Cleaning Up....."'
            }
        }
    }
}
