pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/OpenDurian/poc-managed-cdn.git', branch: 'master', credentialsId: 'github')
      }
    }
  }
  environment {
    tag = ''
  }
}