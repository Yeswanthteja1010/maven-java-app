pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "Maven-slave"
            }
          
          steps {
             
                echo "my master branch"
          }
        }
   }
}
