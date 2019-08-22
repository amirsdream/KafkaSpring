pipeline {
  agent {kubernetes}
  stages {
    stage('Init code') {
      steps {
        sh '''echo "hello world";
'''
      }
    }
  }
  environment {
    HOST = '192.168.2.50'
  }
}