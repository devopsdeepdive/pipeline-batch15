pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/devopsdeepdive/pipeline-batch15.git', branch: 'master', credentialsId: 'github_cred')
      }
    }

  }
}