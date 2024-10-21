pipeline {
   agent any
   stages {
       stage('Build') {
           steps {
               echo 'Building..'
               sh 'ls'
               sh 'ls -l'
               sh 'nix build s#lilex'
               archiveArtifacts artifacts: 'result/*'
           }
       }
   }
 }
