pipeline {
    agent {
        label 'master'
    }
    stages {
        stage('build and push') {
            steps{
            when {
                branch 'main'
            }
            sh "docker build -t docker/getting-started ."

           
        }
      }
    }
}
