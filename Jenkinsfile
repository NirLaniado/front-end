pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''echo \'this is build time"
'''
        sh 'npm install'
      }
    }

    stage('test') {
      steps {
        sh 'npm install'
        sh 'npm test'
      }
    }

    stage('package') {
      steps {
        sh 'npm install'
        sh 'npm run package'
      }
    }

  }
}