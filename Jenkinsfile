pipeline {
  agent none
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'python --version'
          }
        }

        stage('') {
          steps {
            echo 'Hallo'
            timestamps() {
              sleep 1
            }

          }
        }

      }
    }

  }
}