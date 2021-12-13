pipeline {
  agent any
  stages {
    stage('Example Build') {
      steps {
        sh 'echo Hello World'
      }
    }
    stage('Example Deploy') {
      when {
        branch 'main'
      }
      steps {
        sh 'echo Deploying'
      }
    }
  }
}
