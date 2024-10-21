pipeline {
   agent any
   stages {
       stage('Build') {
           steps {
               echo 'Building..'
               sh 'nix build s#lilex'
               archiveArtifacts artifacts: 'result/*'
           }
       }
   }
 }
