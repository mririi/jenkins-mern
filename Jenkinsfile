pipeline {
    agent any
    environment {
        NPM_CONFIG_CACHE = "${WORKSPACE}/.npm"
    }
    stages {
        stage('build') {
            steps {
                sh "npm install"
            }
        }
    }
}
