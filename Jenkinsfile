pipeline {
  agent {
    docker {
      image 'node:7-alpine'
    }
    
  }
  stages {
    stage('Prepare gems') {
      agent any
      steps {
        sh 'node --version'
      }
    }
  }
}