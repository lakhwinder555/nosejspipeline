pipeline {
    agent any
       docker {
            image 'node:lts-buster-slim'
            args '-p 3000:3000'
        }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
               
            }
        }
        stage('Deliver') { 
            steps { 
              
            }
        }
    }
}
