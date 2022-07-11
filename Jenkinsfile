pipeline {
    agent any
      stages {
        
  
         
          stage('Docker Build') {
              steps {
           
               sh ' sudo touch /var/run/docker.sock '


               sh 'docker build -t contnode .'
      }
    }
             
      }
}
  
