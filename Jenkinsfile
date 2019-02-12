pipeline {
  agent any
  stages {
    stage('Initialze') {
      steps {
        echo 'Hello'
      }
    }
    stage('Build') {
      steps {
        sh 'docker build -t helloworld .'
      }
    }
  }
}