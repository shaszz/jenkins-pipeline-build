pipeline {
  agent any
  stages {
    stage('Say Hello') {
      steps {
        script {
          if (isUnix()) {
            sh 'echo Hello from Unix-like shell'
          } else {
            bat 'echo Hello from Windows CMD'
          }
        }
      }
    }
  }
}
