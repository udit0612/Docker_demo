pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''cd /var/lib/jenkins/workspace/Docker_demo_master
docker build -t udit .'''
      }
    }
  }
}