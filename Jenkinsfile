pipeline {
   agent any
   stages {
       stage('Build') {
           steps {
               echo 'PATH=' + env.PATH
               sh "echo 'Starting long-running command'"
               sh 'ls'
           }
       }
   }
 }
