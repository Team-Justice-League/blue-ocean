pipeline {
  agent none
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'test'
          }
        }

        stage('Parallel') {
          steps {
            echo 'parallel'
          }
        }

      }
    }

    stage('Build') {
      steps {
        echo 'build'
      }
    }

    stage('Clean Up') {
      steps {
        echo 'Clean Up'
      }
    }

  }
}