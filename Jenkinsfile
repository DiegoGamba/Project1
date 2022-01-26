pipeline {
    options {
        timeout(time: 1, unit: 'HOURS')
    }
    agent {
        label 'master'
    }
    stages {
        stage('build and push') {
            when {
                branch 'master'
            }
            sh "docker build -t docker/getting-started ."

           
        }
    }
}
