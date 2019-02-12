pipeline {
  agent any
  stages {
    stage('Initialsation') {
      steps {
        sh 'echo "Service docker start"'
      }
    }
    stage('Build') {
      steps {
        sh 'echo "./gradlew build Image"'
      }
    }
    stage('Push') {
      steps {
        sh 'echo "Push docker image"'
      }
    }
  }
}