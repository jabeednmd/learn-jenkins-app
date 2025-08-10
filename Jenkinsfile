pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build Stage'
            }
        }
        stage('Test') {
            steps{
                sh '''
                    if [ -f build/index.html ]; then
                        echo "✅ index.html exists in build directory"
                    else
                        echo "❌ index.html not found in build directory"
                        exit 1
                    fi
                '''
            }
        }

    }
}
