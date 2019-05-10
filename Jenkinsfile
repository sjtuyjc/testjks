pipeline {
    agent any
    stages {
        stage('Build') {
            echo 'Building....'
        }
        stage('Test') {
            sh label: '', script: 'python3 a1.py'
        }
        stage('Deploy') {
            echo 'Deploying....'
        }
    }
}
