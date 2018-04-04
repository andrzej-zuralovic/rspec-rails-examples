pipeline {
  agent any
  stages {
    stage('Prepare gems') {
      agent any
      steps {
        sh 'ruby -v'
      }
    }
    stage('Rspec') {
      steps {
        sh '/bin/bash && bundle exec rspec'
      }
    }
  }
}