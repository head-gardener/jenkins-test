pipeline {
   agent any
   environment {
   }
   stages {
       stage('Build') {
           steps {
               echo 'Building..'
               sh 'ls'
               sh 'nix build s#lilex'
               archiveArtifacts artifacts: 'result/*'
           }
       }
   }
 }
