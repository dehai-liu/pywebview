pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Insert build steps here
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // Insert test steps here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Insert deploy steps here
            }
        }
    }

    post {
        always {
            echo 'Cleaning up...'
            // Insert cleanup steps here
        }
        success {
            echo 'Pipeline succeeded!'
        }
        failure {
            echo 'Pipeline failed.'
        }
    }
}
