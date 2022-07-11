pipeline {
    agent any
      stages {
        
  
         
          stage('Docker Build') {
              steps {
               sh 'sudo chgrp $USER /lib/systemd/system/docker.socket
'
               sh ' sudo chmod g+w /lib/systemd/system/docker.socket'

               sh 'docker build -t contnode .'
      }
    }
             
      }
}
  
