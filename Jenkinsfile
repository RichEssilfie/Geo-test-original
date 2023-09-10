pipeline {
     agent any
     stages {
         stage ('maven clean') {
         steps {
            sh 'opt/mavenbin/mvn clean'
         }
     }
     stage ('maven install'){
         steps{
            sh 'opt/maven/bin/mvn install'
            
         }
     }  
     stage ('maven package'){
         steps{
            sh 'opt/maven/bin/mvn package'
         }
     } 

   }

}