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
        retry(count: 3)
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deployed'
      }
    }

  }
}