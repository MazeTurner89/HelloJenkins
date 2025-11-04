pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git url: 'https://github.com/MazeTurner89/HelloJenkins.git', branch: 'main'
            }
        }
        stage('Build Project') {
            steps {
                echo "Building the project..."
            }
        }
        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }
    }
}
