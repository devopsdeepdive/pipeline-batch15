pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/devopsdeepdive/pipeline-batch15.git', branch: 'master', credentialsId: 'github_cred')
      }
    }

    stage('Build') {
      steps {
        sh 'echo "Build successful"'
      }
    }

    stage('Test') {
      steps {
        sh 'echo "testing successful"'
      }
    }

  }
}