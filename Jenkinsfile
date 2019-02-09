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
    stage('Push') {
      steps {
        sh 'echo "./gradlew pushImage"'
      }
    }
    stage('Test') {
      steps {
        echo 'testing'
      }
    }
  }
}