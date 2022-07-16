pipeline {
    agent any
      stages {
        
  
         
          stage('Docker Build') {
              steps {
                  
                  
               sh 'sudo chmod 666 /var/run/docker.sock'
               sh 'sudo systemctl reload docker'
               sh 'docker build -t contnode .'
      }
    }
       
             
          
          stage(' image  container') {
             steps {
               sh 'docker images'

      }
    }
          
                    stage(' run  docker') {
             steps {
               sh ' docker run contnode'

      }
    }
          
      }
}
  
