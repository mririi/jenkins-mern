pipeline {
    agent {
        docker {
            image 'alpine:3.12.0'
            args '-u root'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'npm install'
            }
        }
    }
}