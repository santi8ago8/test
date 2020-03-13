pipeline {
  agent none
  stages {
    stage('File Download') {
      parallel {
        stage('connecting') {
          steps {
            echo 'connecting'
          }
        }

        stage('downloading') {
          steps {
            echo 'ok'
            sh 'echo "test"'
          }
        }

      }
    }

  }
}