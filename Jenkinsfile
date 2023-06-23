pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from Git repository
                git 'https://github.com/Shivaraju1996/Hello-world.git'
            }
        }

        stage('Build') {
            steps {
                // Perform build steps here
                // For example:
                sh 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                // Run tests
                // For example:
                sh 'mvn test'
            }
        }

        stage('Deploy') {
            steps {
                // Deploy the application
                // For example:
                sh 'mvn deploy'
            }
        }
    }
}
