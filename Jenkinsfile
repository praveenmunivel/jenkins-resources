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
        echo 'Build Success'
      }
    }

    stage('Test') {
      steps {
        sleep 5
        echo 'Slept'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployed'
      }
    }

  }
}