pipeline {
    agent none
    stages {
        stage('Back-end') {
            agent {
                docker { image 'hristodinev123/docker-web' }
            }
            steps {
                sh 'docker run -d -p 8080 docker-web .'
            }
        }
        stage('Front-end') {
            agent {
                docker { image 'hristodinev123/docker-db' }
            }
            steps {
                sh 'docker run -d -p 8080 docker-db .'
            }
        }
    }
}