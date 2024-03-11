pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                
                git 'https://github.com/Jawad151/MLOPS-Task3.git'
            }
        }
        
        stage('Print Message') {
            steps {
                // Print a message
                echo "Hello from the Task3 of MLOPS"
            }
        }
    }
}
