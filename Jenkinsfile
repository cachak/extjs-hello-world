pipeline {
    agent any
    stages {
        stage('Build Image') {
            steps {
                sh "echo build image NPM_AUTH_TOKEN : ${NPM_AUTH_TOKEN} "
                sh 'docker compose -f docker-compose.yml build'
            }
        }
    }
}
