pipeline {
  agent any
  stages {
    stage('Checklout code') {
      steps {
        git(url: 'https://github.com/gyorgy-s/jenkins_test_repo', branch: 'dev')
      }
    }

  }
}