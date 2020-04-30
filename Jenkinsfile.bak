pipeline {
    agent any
    paramenters {
        choice(name:'PerformMavenRelease',choices:'False\nTrue',description:'desc')
        password(name:'CredsToUse',description:'Apassword to build with',defaultValue:'')
    }
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
                echo 'Deploying....'
            }
        }
    }
}
