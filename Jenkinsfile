pipeline {
    agent any

    environment {
        DIRECTORY_PATH = "/home/user/project"
        TESTING_ENVIRONMENT = "Staging Server"
    }

    stages {
        stage('Build') {
            steps {
                echo "Fetching code from ${DIRECTORY_PATH}"
            }
        }
        stage('Test') {
            steps {
                echo "Testing on ${TESTING_ENVIRONMENT}"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploying..."
            }
        }
    }
}
