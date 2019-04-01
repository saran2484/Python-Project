pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Success'
      }
    }
    stage('Test') {
      steps {
        git(url: 'https://github.com/saran2484/Python-Project.git', branch: 'cloud')
      }
    }
    stage('deploy') {
      steps {
        echo 'Welcome'
      }
    }
  }
  environment {
    REST = '123'
  }
}