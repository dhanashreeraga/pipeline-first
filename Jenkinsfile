pipeline {
   agent  any
    stages {
         stage('build'){
             steps{
                 sh echo "it is build"
             }
         }
         stage('test'){
             step{
                sh 'sleep 10'
                  echo "test the app"
             }
         }
         stage('deploy'){
            step{
                 sh echo "deploy the app"
            }

         }
    }

}
