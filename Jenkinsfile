pipeline {
     agent any
     tools{
        maven 'M2_HOME'
     }
     stages {
         stage ('maven clean') {
         steps {
            'mvn clean'
         }
     }
     stage ('maven install'){
         steps{
            'mvn install'
            
         }
     }  
     stage ('maven package'){
         steps{
            'maven package'
         }
     } 

   }

}