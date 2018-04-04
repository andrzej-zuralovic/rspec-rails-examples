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
        sh 'bundle exec rspec'
      }
    }
  }
}