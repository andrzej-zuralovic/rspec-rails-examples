pipeline {
  agent any
  stages {
    stage('Prepare gems') {
      agent {
        docker {
          image 'node:7-alpine'
        }
        
      }
      steps {
        sh 'node --version'
      }
    }
  }
}