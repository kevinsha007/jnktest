pipeline {
    
    agent { node { label 'ecsAgent' } } 

    stages {
        stage('Checking Flutter') {
            steps {
                echo 'Checking Flutter..'
                sh 'flutter doctor'
                sh 'flutter clean'
                sh 'flutter pub get'
            }
        }
        stage('Building') {
            steps {
                echo 'Building..'
                sh 'build web'
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