pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/rosinalexis/curriculum-app', branch: 'master')
      }
    }

    stage('') {
      steps {
        sh 'ls -la'
      }
    }

  }
}