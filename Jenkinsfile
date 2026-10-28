pipeline {
    agent any
    stages {
        stage('Get Code') {
            steps {
                checkout scm
            }
        }
        stage('Test') {
            steps {
                sh 'python3 test_app.py'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the app...'
            }
        }
    }
}
