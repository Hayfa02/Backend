pipeline {
    agent any
      stages {
        
  
         
          stage('Docker Build') {
              steps {
                  
              
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
                  sh 'docker ps'

      }
    }
          
      }
}
  
