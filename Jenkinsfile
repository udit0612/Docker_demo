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
    stage('Push Image') {
      steps {
        echo '"Pushed docker image into the registry"'
      }
    }
    stage('test') {
      steps {
        echo 'testing'
      }
    }
  }
}