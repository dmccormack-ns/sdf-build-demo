node('linux') {
  def maven = docker.image('maven:latest')
  maven.pull() // make sure we have the latest available from Docker Hub
  maven.inside {
    sh 'echo test'
  }
}
