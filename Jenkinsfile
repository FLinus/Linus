pipeline {
  agent {
    docker {
      image 'python'
    }

  }
  stages {
    stage('build') {
      steps {
        sh 'python --version'
      }
    }
    stage('Test'){
    steps {
    sh 'apt install -y ipython'
    }
    }
  }
}