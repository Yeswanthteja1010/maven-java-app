pipeline {
    
    agent none
    
   stages {
        
        stage('Build'){
            
            agent {
                label "jenkins-slave1"
            }
          
          steps {
             
                echo "my master branch"
          }
        }
   }
}
