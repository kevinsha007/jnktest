pipeline {
    
    agent { node { label 'ecsAgent' } } 

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh 'flutter doctor'
                sh 'rsync --help'
                sh 'a'
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