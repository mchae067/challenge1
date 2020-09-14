pipeline {
  agent { dockerfile true }

  stages {
    stage('Hello') {
      steps {
        sh '/usr/games/cowsay Hello World'
      }
    }
  }
}
