pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        dir('/opt/docker/projCert/Dockerfile') {
          sh 'docker build -t my-docker-image .'
        }
      }
    }
  }
}






