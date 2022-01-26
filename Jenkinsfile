pipeline {
    agent {
        label 'main'
    }
    stages {
        stage('build and push') {
            steps{            
            sh "docker build -t docker/getting-started ."    
        }
      }
    }
}
