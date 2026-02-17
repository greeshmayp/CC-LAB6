pipeline {
    agent any

    stages {

        stage('Build Backend Image') {
            steps {
                sh '''
                docker rmi -f backend-app || true
                docker build -t backend-app backend
                '''
            }
        }
stage('Build Backend Image') {
    steps {
        sh '''
        docker rmi -f backend-app || true
        docker build -t backend-app backend
        '''
    }
}


