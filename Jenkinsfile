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

    stage('Build') {
      steps {
        echo 'Building'
        sh 'sudo npm run build'
      }
    }

  }
}