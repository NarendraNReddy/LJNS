pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'Build phase'
            }
        }
        stage('Test') {
            steps {
                sh 'Test phase'
            }
        }
        stage('Deploy') {
            steps {
                sh 'Deploy build'
            }
        }
    }
}