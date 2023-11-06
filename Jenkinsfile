pipeline {
    
    agent { node { label 'ecsAgent' } } 

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'flutter doctor'
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