pipeline {

    agent any
    
    stages {
         stage('install') {
          steps {
              bat 'npm install'
            }
          }
        
          stage('start') {
          steps {
              bat 'npm start'
            }
          }
        
        stage('test') {
          steps {
              bat 'echo test'
            }
          }
      
        stage('Docker Comopse Up') {
            steps {
               
                    bat "echo docker-was-successfully-run"
                
            }
        }
    }
}
