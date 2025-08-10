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
                echo 'Test stage'
                sh 'ls -la "C:\Users\jabee\PycharmProjects\learn-jenkins-app\build\index.html"'
            }
        }

    }
}
