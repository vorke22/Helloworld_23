pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Buils step'
                sleep 10
            }
         }
         stage('Test') {
            steps {
                echo 'Test step'
            }
         }     
         stage('Deploy') {
            steps {
                echo 'Deploy step'
                sleep 10
            }
         } 
         stage('Docker') {
            steps {
                echo 'image step'
            }
        } 
    }
}
