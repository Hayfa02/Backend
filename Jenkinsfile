pipeline {
    agent any
      stages {
        
  
         
          stage('Docker Build') {
              steps {
               sh 'sudo su /var/run/docker.sock'

               sh 'docker build -t contnode .'
      }
    }
             
      }
}
  
