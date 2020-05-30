pipeline {
  /*this the pipeline for the creating kubernetes agents*/
  agent{
    docker {
      image 'maven:3-alpine'
      label 'docker-agent'
      registryUrl 'https://hub.docker.com/'
      registryCredentialsId 'dock'
    }
  }
  stage ('hello') {
    step {
      sh echo 'hellow'
    }
  }
}
