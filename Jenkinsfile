pipeline {
   agent any
   stages {
       stage('Build') {
           steps {
               sh 'ls'
               archiveArtifacts artifacts: 'result/*'
           }
       }
   }
 }
