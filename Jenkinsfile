pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        sh '''echo "Initializing"

yum clean all'''
      }
    }
    stage('Build') {
      steps {
        sh 'docker build -t hello-world .'
      }
    }
  }
}