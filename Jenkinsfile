pipeline {
    agent any
      stages {
        
  
         
          stage('Docker Build') {
              steps {
           
               sh ' RUN usermod -a -G docker jenkins '
               sh ' RUN chown root:docker /var/run/docker.sock '
               sh ' sudo touch /var/run/docker.sock '


               sh 'docker build -t contnode .'
      }
    }
             
      }
}
  
