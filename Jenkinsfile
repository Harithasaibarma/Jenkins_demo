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
        stage('Run Script') {
            steps {
                sh 'bash hello.sh'
            }
        }
    }
}

