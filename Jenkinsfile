pipeline {
  agent any
  stages {
    stage('Init') {
      steps {
        echo 'building...'
        sh '''cd /var/www/html
ls -al'''
      }
    }
    stage('release') {
      steps {
        echo 'Start release'
      }
    }
  }
}