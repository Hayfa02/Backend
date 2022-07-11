pipeline {
    agent any
      stages {
        
  
         
          stage('Docker Build') {
              steps {
           
               sh 'exec chmod 666 /var/run/docker.sock'

               sh 'docker build -t contnode .'
      }
    }
             
      }
}
  
