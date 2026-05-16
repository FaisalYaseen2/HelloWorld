pipeline {

    agent any

    environment {
        VERSION = '1.0'
    }

    stages {

        stage('Build') {
            steps {
                echo "Version is ${VERSION}"
            }
        }

        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
