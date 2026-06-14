pipeline {
    agent any

    tools {
        maven 'Maven'
    }

    stages {

        stage('Checkout') {
            steps {
            echo 'sucessfull'
            }
        }

        stage('Build') {
          steps {
            echo 'sucessfull'
            }}
        }

        stage('Prepare File') {
           steps {
            echo 'sucessfull'
            }
        }

        stage('Run Application') {
          steps {
            echo 'sucessfull'
            }
        }
    }

    post {
        success {
            echo 'Build successful!'
        }
        failure {
            echo 'Build failed!'
        }
    }
}
