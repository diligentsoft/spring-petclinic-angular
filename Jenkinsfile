pipeline {
  agent {
    docker {
      image 'node:6.12.3-alpine'
    }
  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install --save-dev @angular/cli@latest'
        sh 'rm package-lock.json'
        sh 'npm install'
      }
    }
  }
}
