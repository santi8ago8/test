pipeline {
  agent { docker { image 'node:6.3' } }
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
