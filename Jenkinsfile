pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('Workspace') {
            steps{            
            sh "cd /Users/diegogamba"    
        }
    }

        stage('Build') {
            steps{            
            sh "docker build . -t "docker/getting-started""
        }    
    }
  } 
} 
