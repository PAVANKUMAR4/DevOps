pipeline {

    // Define the agent for the pipeline
    agent any

    stages {

        // Checkout stage
        stage('Checkout') {
            steps {
                echo 'This is checkout stage'
                git branch: 'main', url: 'https://github.com/PAVANKUMAR4/DevOps.git'
                echo 'Checkout Completed'
            }
        }

        // Build ID stage
        stage('Build ID') {
            steps {
                echo "This Build JOB ID is ${env.BUILD_ID}"
            }
        }

        // Build Number stage
        stage('Build Number') {
            steps {
                echo "This Build JOB Number is ${env.BUILD_NUMBER}"
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