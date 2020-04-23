pipeline {
  agent {
    node {
      label 'slave1'
    }

  }
  stages {
    stage('checokut') {
      steps {
        git(url: 'https://www.github.com/fullstack-web1/pipe1.git', branch: 'Dev')
      }
    }

  }
}