pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('checkout') {
            steps {
                checkout scm
            }
        }
        stage('list files') {
            steps {
                sh 'ls'
            }
        }
        stage('python') {
            steps {
                sh 'python3.9 mypy.py'
            }
        }
    }
}
