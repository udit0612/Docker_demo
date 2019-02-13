pipeline {
  agent any
  stages {
    stage('initialize') {
      steps {
        sh '''echo "Starting"
yum clean all'''
      }
    }
    stage('Build') {
      steps {
        sh 'docker build -t hello-world .'
      }
    }
    stage('Test') {
      steps {
        echo 'test'
      }
    }
    stage('Push') {
      steps {
        echo './gradlew pushImage'
      }
    }
  }
}