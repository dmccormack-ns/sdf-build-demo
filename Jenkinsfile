pipeline {
  agent {
    docker {image 'hello-world'}
  }
  stages {
    stage('Test docker') {
      step {
        sh 'echo test'
      }
    }
  }
}
