pipeline {
  agent any
  stages {
    stage('development') {
      steps {
        echo 'dev stage'
      }
    }

    stage('built') {
      steps {
        echo 'built stage'
      }
    }

    stage('unit test') {
      steps {
        echo 'unit testing'
      }
    }

    stage('deployment') {
      steps {
        echo 'deploy the code'
      }
    }

  }
}