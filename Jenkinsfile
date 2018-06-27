pipeline {
  agent {
    docker {
      image 'busybox'
      args 'ls'
    }
    
  }
  stages {
    stage('run') {
      steps {
        sh 'ks'
      }
    }
  }
}
