pipeline {
  agent any
  stages {
    stage('Sample Run') {
      steps {
        echo '"Hello World"'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build Success'
          }
        }

        stage('Parallel Build') {
          steps {
            echo 'Running Parallely'
          }
        }

        stage('2nd Parallel') {
          steps {
            echo 'Second Parallel'
          }
        }

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