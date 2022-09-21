pipeline {
  agent {
    node {
      label 'Docker'
    }

  }
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'testing'
          }
        }

        stage('Parallel') {
          steps {
            echo 'parallel testing'
          }
        }

      }
    }

    stage('Build') {
      steps {
        echo 'Building'
      }
    }

    stage('Clean') {
      steps {
        echo 'cleaning'
      }
    }

  }
}