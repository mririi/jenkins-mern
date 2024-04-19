pipeline {
    agent any
    environment {
        PATH = "/home/vagrant/.nvm/versions/node/v21.7.3/bin:${env.PATH}"
    }
    stages {
        stage('build') {
            steps {
                sh "pwd"
                sh "ls"
                sh "npm install"
            }
        }
    }
}