# Jenkinsfile
#
pipeline {
agent any
stages {
  stage ('prepare') {
    steps {
      echo 'preparing environment...'
      sh 'uname -a'
    }
  }
  stage ('build') {
    steps {
      echo 'building the app...'
    }
  }
  stage('test') {
     steps {
      echo 'testing the app...'
    }
  }
  stage('deploy') {
    steps {
      echo 'deploying the app...'
    }
  }
}
}
