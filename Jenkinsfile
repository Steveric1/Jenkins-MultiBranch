pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
        stage('cat REAME') {
            when {
                branch "fix-*"
            }
            steps {
                sh 'cat README.md'
            }
        }
    }
}
