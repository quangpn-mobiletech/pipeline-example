pipeline {
  agent {
    docker {
      image 'busybox'
      args 'ls'
    }
    
  }
  stages {
    stage('stage-ex') {
      steps {
        sh 'ks'
      }
    }
  }
}
