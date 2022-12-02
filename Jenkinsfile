pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'hello'
      }
    }

    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'hello'
          }
        }

        stage('integration') {
          steps {
            echo 'integration'
          }
        }

      }
    }

    stage('deploiement') {
      steps {
        echo 'deploiement'
      }
    }

  }
}