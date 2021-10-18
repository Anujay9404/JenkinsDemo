pipeline {
    tools{
        maven 'Maven3.8.3'
    }
    agent any
    stages {
        stage('Clean') {
            steps {
                 echo 'Cleaning..'
                 bat 'mvn -B -DskipTests clean'
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