pipeline {
  agent any
  stages {
    stage('Prepare gems') {
      agent any
      steps {
        sh 'echo $USER'
      }
    }
    stage('Rspec') {
      steps {
        sh '/bin/bash && bundle exec rspec'
      }
    }
  }
}