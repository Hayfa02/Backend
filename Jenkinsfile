pipeline {
    agent any
      stages {
        
  
         
          stage('Docker Build') {
              steps {
               sh ' export SUDO_ASKPASS=$HOME/.local/bin/sudo-askpass'
               sh 'alias sudo='sudo -A'
               sh 'sudo /var/run/docker.sock'

               sh 'docker build -t contnode .'
      }
    }
             
      }
}
  
