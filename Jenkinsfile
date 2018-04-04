pipeline {
  agent any
  stages {
    stage('Prepare gems') {
      agent {
        docker {
          image 'ruby:2.5.0'
        }
        
      }
      steps {
        sh 'ruby -v'
      }
    }
  }
}