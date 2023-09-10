pipeline {
     agent any
     stages {
        tools M2
         stage ('maven clean') {
         steps {
            sh 'opt/mavenbin/mvn clean'
         }
     }
     stage ('maven install'){
         steps{
            sh 'opt/maven/bin/mvn install'
            sh  'echo hi'
         }
     }  
     stage ('maven package'){
         steps{
            sh 'opt/maven/bin/mvn package'
         }
     } 

   }

}