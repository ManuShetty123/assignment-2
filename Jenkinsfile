pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Starting Build...'
                // Adjust to 'mvn package' if you are using Maven
                sh 'npm install || echo "Simulating npm install for lab purposes"'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Running Tests...'
                sh 'echo "All unit tests passed successfully!"'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying Application...'
                sh 'echo "Copying artifacts to deployment server"'
            }
        }
    }
}
