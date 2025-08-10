pipeline {
    agent {
        docker {
            image 'node:18-alpine'
            reuseNode true
        }
    }

    stages {
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
    }
}