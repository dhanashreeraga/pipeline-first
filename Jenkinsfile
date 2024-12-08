pipeline {
   agent any
    stages {
         stage('build'){
             steps{
                  sh 'sleep 10'
                 echo "it is build"
             }
         }
             
                 stage('test'){
             steps{
                sh 'sleep 10'
                  echo "test the app"
             }
             }
         
         stage('deploye'){
            steps{
                sh 'sleep 20'
                  echo "deploy the app"
            }
         }
         }
    }


