pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        dir('/opt/docker/projCert/website/Dockerfile') {
          sh 'sudo docker build -t my-docker-image .'
        }
      }
    }
  }
}






