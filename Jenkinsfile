pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps { checkout scm }
    }
    stage('Say Hello') {
      steps {
        echo "Hello from Jenkins pipeline!"
        sh 'echo building...'
      }
    }
  }
  post {
    always { echo "Done (success or fail)." }
  }
}
