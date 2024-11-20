pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Step 1: Checking out source code...'
            }
        }
        stage('Setup') {
            steps {
                echo 'Step 2: Setting up environment...'
            }
        }
        stage('Test') {
            steps {
                echo 'Step 3: Running tests...'
            }
        }
        stage('Cleanup') {
            steps {
                echo 'Step 4: Cleaning up workspace...'
            }
        }
    }
}
