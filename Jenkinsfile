pipeline {
  agent {
    docker {image 'hello-world'}
  }
  stages {
    stage('Test docker') {
      sh 'echo test'
    }
  }
}
