pipeline {
   agent any
    stages {
         stage('build'){
             steps{
                  sh 'sleep 10'
                 echo "it is build"
             }
         }


         stage('parrael stage'){
             parallel{
                 stage(test1){
             steps{
                sh 'sleep 10'
                  echo "test the app"
             }
             }
         }
         stage('test2'){
            steps{
                sh 'sleep 20'
                  echo "deploy the app"
            }
         }
         }
         
         stage('parrael1 stage'){
             parallel{
                 stage('test3'){
             steps{
                sh 'sleep 10'
                  echo "test the app"
             }
             }
         }
         stage('test4'){
            steps{
                sh 'sleep 20'
                  echo "deploy the app"
            }
         }
         }
    }

}
