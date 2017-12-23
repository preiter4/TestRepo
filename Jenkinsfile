pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'echo "Hello!!!!!!!!"'
      }
    }
    stage('Deploy') {
      steps {
        bat 'echo "World"'
      }
    }
    stage('Release') {
      parallel {
        stage('Release') {
          steps {
            bat 'echo "There"'
          }
        }
        stage('') {
          steps {
            bat 'echo "Stepppppppooooo"'
          }
        }
      }
    }
  }
}
