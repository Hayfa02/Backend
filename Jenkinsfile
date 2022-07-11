pipeline {
    agent any
      stages {
        
  
         
          stage('Docker Build') {
              steps {
           
               sh ' docker run --group-add $(stat -c '%g' /var/run/docker.sock) '

               sh 'docker build -t contnode .'
      }
    }
             
      }
}
  
