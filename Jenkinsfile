pipeline {
  agent {
    docker { image 'node:18.12.1' }
  }

  stages {
    stage('Test') {
      steps {
        sh 'node -v'
        sh 'npm -v'
      }
    }
  }
}
