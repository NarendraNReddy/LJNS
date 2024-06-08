pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh "Build"
            }
        }
        stage('Test') {
            steps {
                sh "Test"
            }
        }
        stage('Deploy') {
            steps {
                sh "Deploy"
            }
        }
    }
}