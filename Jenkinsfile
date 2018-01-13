pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('getSourceCode') {
      steps {
        git(url: 'https://github.com/dcarbajosa/somefun.git', branch: 'master')
      }
    }
  }
}