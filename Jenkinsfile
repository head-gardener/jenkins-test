pipeline {
   agent any
   stages {
       stage('Build') {
           steps {
               sh "echo 'Starting long-running command'"
               sh 'ls'
               archiveArtifacts artifacts: 'result/*'
           }
       }
   }
 }
