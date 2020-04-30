pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                input message: 'Deploy to server? (Click "Proceed" to continue)'
                echo 'Deploying....'
            }
        }
    }
}
