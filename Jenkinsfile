  pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World kaushik updated '
                sh 'docker images'
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
