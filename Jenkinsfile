pipeline {

    // Define the agent for the pipeline
    agent {
        label 'pavan'
    }

    stages {

        // Checkout stage
        stage('Checkout') {
            steps {
                echo 'This is checkout stage'
            }
        }

        // Build stage
        stage('Build') {
            steps {
                echo 'This is build stage'
            }
        }

        // Test stage
        stage('Test') {
            steps {
                echo 'This is test stage'
            
            }
        }

        // Docker Build stage
        stage('Docker Build') {
            steps {
                echo 'This is docker build stage'
            }
        }

        // Deploy stage
        stage('Deploy') {
            steps {
                echo 'This is deploy stage'
            }
        }
    }
}