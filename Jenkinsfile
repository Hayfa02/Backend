pipeline {
    agent any
      stages {
        
  
         
          stage('Docker Build') {
              steps {
           
               sh 'sudo chmod 777 /var/run/docker.sock'

               sh 'docker build -t contnode .'
      }
    }
             
      }
}
  
