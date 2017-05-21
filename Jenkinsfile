pipeline {
  agent any
  stages {
    stage('Init Pipeline') {
      steps {
        docker.image('hello-world').inside {
          sh 'echo Hello'
      }
    }
  }
}
}
