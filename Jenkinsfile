pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'python --version'
                bat 'python main.py'
            }
        }
    }
}