pipeline {
  agent { label 'codebuilder' }
  stages {
    stage('Install') {
      steps { sh 'apk add -U nodejs' }
    }
    stage('Build') {
      steps { sh 'node --version' }
    }
  }
}
