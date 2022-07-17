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
          
                 stage(' docker  container') {
             steps {
               sh 'docker run -p 4000:4000 -it contnode'

      }
    }
          

          
      }
}
  
