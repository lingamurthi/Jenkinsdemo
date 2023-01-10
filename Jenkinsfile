pipeline {
    agent {
        docker {
            image 'node:alpine-latest'
            args '-p 3000:3000'
        }
    }
  
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
       
    }
}
