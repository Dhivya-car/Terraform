pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build steps are getting excuted'
          }
        }

        stage('Build1') {
          steps {
            echo 'Build second part of the code'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'lets deploy testing server'
      }
    }

  }
}