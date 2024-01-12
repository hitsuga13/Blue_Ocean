pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/hitsuga13/Blue_Ocean', branch: 'main ')
      }
    }

    stage('Testing') {
      steps {
        echo 'Default'
      }
    }

    stage('Pull?') {
      steps {
        echo 'How to pull?'
      }
    }

  }
}