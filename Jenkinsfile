pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        sh '''echo "Project is initiallizing"
yum clean all'''
      }
    }
    stage('Build') {
      steps {
        sh 'docker build -t hello-world .'
      }
    }
    stage('test') {
      steps {
        echo 'testing'
      }
    }
    stage('Push') {
      steps {
        echo './gradlew pushImage'
      }
    }
  }
}