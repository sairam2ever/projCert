pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        dir('projCert/Dockerfile') {
          sh 'sudo docker build -t my-docker-image .'
        }
      }
    }
  }
}






