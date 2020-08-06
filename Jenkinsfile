pipeline {
  agent any
  stages {
    stage('buzz buzz') {
      parallel {
        stage('buzz buzz') {
          steps {
            echo 'Bees Buzz!'
          }
        }

        stage('Bees Bees') {
          steps {
            echo 'Buzz, Bees, Buzz'
          }
        }

        stage('Bees Buzzing') {
          steps {
            echo 'Bees Buzzing'
          }
        }

      }
    }

  }
  environment {
    buzz = 'buzz'
    Bees = 'Bees'
  }
}