pipeline {
    agent any
    stages {
        stage('Check Docker Version') {
            steps {
                echo 'Step 1: Checking Docker version...'
                sh 'docker version'
            }
        }
        stage('List Running Containers') {
            steps {
                echo 'Step 2: Listing running Docker containers...'
                sh 'docker ps'
            }
        }
    }
}
