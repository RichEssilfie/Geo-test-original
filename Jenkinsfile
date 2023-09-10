pipeline {
     agent any
     stages {
        tools M2
         stage ('maven clean') {
         steps {
            sh 'mvn clean'
         }
     }
     stage ('maven install'){
         steps{
            sh 'mvn install'
            sh  'echo hi'
         }
     }  
     stage ('maven package'){
         steps{
            sh 'mvn package'
         }
     } 

   }

}