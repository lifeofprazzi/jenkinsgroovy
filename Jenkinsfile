pipeline {
  agent {
    docker { image 'node:16-alpine' }
  }
  stages {
    stage('DockerAgentVersion') {
      steps {
        sh 'node --version'
      }
    }
  }
}
