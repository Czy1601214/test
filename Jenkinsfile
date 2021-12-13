pipeline {
  agent none
  stages {
    stage('start') {
      parallel {
        stage('start') {
          steps {
            echo 'start'
          }
        }

        stage('init') {
          steps {
            echo 'init'
          }
        }

      }
    }

  }
}