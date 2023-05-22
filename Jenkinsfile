/* Requires the Docker Pipeline plugin */
/* test something in gerrit really quick */
pipeline {
    agent { docker { image 'golang:1.19.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
