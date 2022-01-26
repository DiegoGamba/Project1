pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('build and push') {
            steps{            
            sh "cd /Users/diegogamba"    
        }
            steps{            
            sh "docker build . -t docker/getting-started"    
        }
      }
    }
}
