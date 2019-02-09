pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Hello its initializing'
      }
    }
    stage('Build') {
      steps {
        sh 'docker build -t hello-world .'
      }
    }
  }
}