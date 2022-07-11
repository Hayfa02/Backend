pipeline {
    agent any
      stages {
        
  
         
          stage('Docker Build') {
              steps {
           
               sh ' RUN chown root:docker /var/run/docker.sock '
               sh ' sudo touch /var/run/docker.sock '


               sh 'docker build -t contnode .'
      }
    }
             
      }
}
  
