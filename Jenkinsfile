pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('Verificar Docker'){
            steps{
                sh "cd /Users/diegogamba" 
                sh "docker ps" 
                sh "docker images" 
                sh "cat Dockerfile"            
            }
        }
        stage('Workspace') {
            steps{                                     
            sh "docker build . -t name:getting-started"    
          }    
       }
    }
}   
