pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo 'Cloning repo...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
                // Example: sh 'npm install' or mvn clean install
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example: sh 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Example: sh 'docker run ...'
            }
        }
    }
}
