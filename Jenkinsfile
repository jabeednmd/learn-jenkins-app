pipeline {
    agent {
        docker {
            image 'node:18-alpine'
            reuseNode true
        }
    }
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
    }
}
