pipeline {
  agent any
  stages {
    stage('Hello') {
      parallel {
        stage('Hello') {
          steps {
            echo 'Hello World kaushik updated '
            sh 'docker images'v1.2 
          }
        }

        stage('Hello2') {
          steps {
            sh 'docker images'
            sh 'echo \'Hello\''
          }
        }

      }
    }

    stage('Buid') {
      steps {
        echo 'Building'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing'
      }
    }

    stage('Release') {
      steps {
        echo 'Releasing'
      }
    }

  }
}
