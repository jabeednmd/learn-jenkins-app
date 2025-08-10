pipeline {
    agent any

    stages {
        agent{
            docker {
                image 'node:18-alpine'
            }
        }
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps{
                sh '''
                    npm test
                '''
            }
        }

    }
}
