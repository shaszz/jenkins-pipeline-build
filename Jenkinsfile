pipeline {
  agent any
  stages {
    stage('Install & Test') {
  steps {
    sh 'npm ci'
    sh 'npm test'
  }
}
  }
}
