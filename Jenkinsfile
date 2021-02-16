Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'python:alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
