pipeline {
    agent any
      stages {
        
  
         
          stage('Docker Build') {
              steps {
                  
              
               sh 'docker build -t contnode .'
      }
    }
       
             
          
          stage(' docker  iamge') {
             steps {
               sh 'docker images'

      }
    }
                stage(' container  iamge') {
             steps {
               sh 'docker ps'

      }
    }
          
                 stage(' docker  container') {
             steps {
               sh 'docker run -p 4000:4000 -t contnode'

      }
    }
          

          
      }
}
  
