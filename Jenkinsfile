pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/hitsuga13/Blue_Ocean', branch: 'main ')
      }
    }

    stage('Log') {
      steps {
        sh 'ls -la'
      }
    }

    stage('Testing') {
      steps {
        echo 'Checking '
      }
    }

  }
}