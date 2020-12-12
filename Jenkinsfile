pipeline {
  agent any
  stages {
    stage('Sample Run') {
      steps {
        echo '"Hello World"'
      }
    }

    stage('Build') {
      steps {
        sh 'echo \'PlaceHolder\''
      }
    }

    stage('Test') {
      steps {
        sh 'echo \'Success!!!\''
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo \'Placeholder\''
      }
    }

  }
}