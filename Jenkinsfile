pipeline {
  agent any
  stages {
    stage('Checkout code') {
      steps {
        git(url: 'https://github.com/gyorgy-s/jenkins_test_repo', branch: 'dev')
      }
    }

    stage('cat main.py') {
      steps {
        sh 'cat main.py'
      }
    }

  }
}