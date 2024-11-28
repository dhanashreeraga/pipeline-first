pipeline {
   agent  {
    label 'slave1'
   }
    stages {
         stage('build'){
            agent{
                 label 'slave2'
            }
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
         stage('deploy'){
            steps{
                sh 'sleep 20'
                  echo "deploy the app"
            }

         }
    }

}
