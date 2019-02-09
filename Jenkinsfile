pipeline {
  agent any
  stages {
    stage('initialize') {
      steps {
        sh '''
yum clean all
'''
      }
    }
    stage('Build') {
      steps {
        sh 'docker build -t hello-world .'
      }
    }
  }
}