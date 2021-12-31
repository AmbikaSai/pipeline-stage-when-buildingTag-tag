pipeline{
    agent any
    
    stages{
        stage('Build'){
                  
                      when{
                              building()
                      }
                      
                      
           steps{
               echo 'Hello world building tag'
           }
        }
     }
 }
