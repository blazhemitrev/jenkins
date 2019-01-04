pipeline {
  agent {
    node {
      label 'macos-workers'
    }

  }
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        echo 'editing ....'
        sh 'echo "setting env"'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
  environment {
    PATH = '/usr/local/bin:$PATH'
    LC_ALL = 'en_US.UTF-8'
    LANG = 'en_US.UTF-8'
  }
}