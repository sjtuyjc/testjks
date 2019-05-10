node {
    stage('Build') {
        echo 'Building....'
    }
    stage('Test') {
            steps {
                sh label: '', script: 'python3 a1.py'
            }
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}
