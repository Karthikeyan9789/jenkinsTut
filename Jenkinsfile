pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
                sh 'python3 hello.py'
            }
        }
    }
}