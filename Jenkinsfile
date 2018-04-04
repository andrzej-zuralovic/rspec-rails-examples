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