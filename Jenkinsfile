pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Appajisdsrao/devops-cicd-demo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Building the application..."'
                // Add your actual build command here, e.g., mvn clean package or npm install
            }
        }

        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
                // Add testing commands if applicable
            }
        }

        stage('Deploy') {
            steps {
                sh 'echo "Deploying application..."'
                // Example: sh 'docker build -t my-app .'
            }
        }
    }
}
