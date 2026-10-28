pipeline {
    agent any
    stages {
        stage('Get Code') {
            steps {
                checkout scm
            }
        }
        stage('Show Files') {
            steps {
                sh 'ls -la'
            }
        }
        stage('Run') {
            steps {
                sh 'echo "Hello from my repo. Build number: $BUILD_NUMBER"'
            }
        }
    }
}
