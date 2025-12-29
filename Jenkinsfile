pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Replace with your actual GitHub Repo URL
                git 'https://github.com/jglick/simple-maven-project-with-tests.git' 
            }
        }

        stage('Build') {
            steps {
                echo 'Compiling the application...'
                // sh 'mvn clean package' // Uncomment if you have Maven installed
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application to Kubernetes...'
                echo 'Application successfully deployed!'
            }
        }
    }
}
