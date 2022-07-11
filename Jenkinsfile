pipeline {
    agent any
      stages {
        
  
         
          stage('Docker Build') {
              steps {
               sh 'sudo -rs chmod 666 /var/run/docker.sock'
               sh 'docker build -t contnode .'
      }
    }
             
      }
}
  
