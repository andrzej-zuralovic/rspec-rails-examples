pipeline {
  agent any
  stages {
    stage('Prepare gems') {
      steps {
        sh '''#!/bin/bash
gem install bundler'''
        sh '''#!/bin/bash
bundle install'''
      }
    }
    stage('Rspec') {
      steps {
        sh '''#!/bin/bash
bundle exec rspec'''
      }
    }
  }
}