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
        sh '''echo \'PlaceHolder\'
sh \'echo edited placeholder\''''
      }
    }

    stage('Test') {
      steps {
        sh '''sh \'sleep 5\'
sh \'echo Success!!!\''''
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo \'Placeholder\''
      }
    }

  }
}