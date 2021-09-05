pipeline {
    agent {
        label 'master' {
            image 'python:3.5.1'
        }
    }
    stages {
        stage("build") {
            steps {
                sh 'python --version'
            }
        }
    }

}

