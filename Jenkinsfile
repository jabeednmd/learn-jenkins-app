pipeline {
    agent {
        docker {
            image 'node:18-alpine'
            reuseNode true
        }
    }
        stage('Test') {
            sh 'npm test'
        }
}
