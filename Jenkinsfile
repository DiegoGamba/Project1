pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('Workspace') {
            steps{            
            sh "cd /Users/diegogamba"                
            sh "docker build . -t name:getting-started"    
          }    
       }
    }
}   
