pipeline {
    agent any
    
    tools {
        
    }

    stages {
        stage("install") {
            steps {
                echo "install progress"
            }
        }
        stage("build") {
            steps {
                echo "buil progress"
            }
        }
    } 
    
    post {
        success {
            echo "SUCCESSFUL"
        }
        failure {
            echo "FAILED"
        }
    }
}