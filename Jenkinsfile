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
}