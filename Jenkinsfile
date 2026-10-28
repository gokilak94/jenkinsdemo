pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'GitHub source code checkout'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application1'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing the application'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage completed'
            }
        }
    }
}
