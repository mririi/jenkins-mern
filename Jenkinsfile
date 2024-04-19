pipeline {
    agent { docker { image 'node:12-alpine' } }
    stages {
        stage('build') {
            steps {
                sh "npm install"
            }
        }
    }
}