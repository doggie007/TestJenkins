pipeline {
    agent { docker { image 'python:3.9.1-alpine' } }
    stages {
        stage('build') {
            steps {
                bat 'python --version'
            }
        }
    }
}