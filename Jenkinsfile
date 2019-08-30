pipeline {
  agent any
  stages {
    stage('Init code') {
      steps {
        sh '''echo "hello world";
'''
      }
    }
    stage('build project') {
      steps {
        sh 'mvn --version'
      }
    }
  }
  environment {
    HOST = '192.168.2.50'
  }
}