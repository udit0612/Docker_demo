pipeline {
  agent any
  stages {
    stage('Initialze') {
      steps {
        sh '''echo "Initialiing he project"
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