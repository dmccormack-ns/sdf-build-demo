pipeline {
  agent {
    docker {image 'hello-world'}
  }
  stages {
    stage('Test docker') {
      steps {
        sh 'echo test'
      }
    }
  }
}
