pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building your code...'
                // Add your build commands here
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your test commands here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying your application...'
                // Add your deployment commands here
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded! Triggering additional actions...'
            // Add actions to perform on successful build
        }
        failure {
            echo 'Pipeline failed! Handling failure...'
            // Add actions to perform on build failure
        }
    }
}
