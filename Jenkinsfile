pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh 'bundle install'
      }
    }
    stage('Rspec') {
      steps {
        sh 'gem -v'
      }
    }
  }
}
