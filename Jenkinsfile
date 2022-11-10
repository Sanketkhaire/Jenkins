pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                ECHO "hello world"
                sh 'make'
                sh './primeNumbers'
            }
        }
    }
}
