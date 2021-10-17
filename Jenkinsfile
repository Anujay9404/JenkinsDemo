pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                 echo 'Cleaning..'
                 sh 'mvn -B -DskipTests clean'
            }
        }
        
        stage('Test') {
            steps {
                echo 'test app stage...'
            }
        }
        
        stage('Integartion') {
            steps {
                echo 'third stage'
            }
        }
        
    }
}