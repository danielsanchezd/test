pipeline {
  agent any
  stages {
    stage('Test') {
      agent {
        docker {
          image 'jenkinsci/jnlp-slave'
        }

      }
      steps {
        sh 'echo "Test"'
      }
    }
    stage('Build') {
      agent {
        docker {
          image 'jenkinsci/jnlp-slave'
        }

      }
      steps {
        sh 'echo "Building"'
      }
    }
    stage('Deploy') {
      agent {
        docker {
          image 'jenkinsci/jnlp-slave'
        }

      }
      steps {
        sh 'echo "Deploying"'
      }
    }
  }
}