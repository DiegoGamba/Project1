pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('build and push') {
            steps{            
            sh "docker build -t docker/getting-started ."    
        }
      }
    }
}
