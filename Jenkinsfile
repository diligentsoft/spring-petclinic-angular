pipeline {
  agent {
    docker {
      image 'node:9.9.0-alpine'
    }
  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install --save-dev @angular/cli@latest'
        sh 'npm install'
      }
    }
  }
}
