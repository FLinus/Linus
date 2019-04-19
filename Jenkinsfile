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
    sh '/data/jenkins/ipy-install.sh'
    }
    }
  }
}