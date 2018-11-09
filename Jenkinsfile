pipeline {
  agent any
  stages {
    stage('Get') {
      steps {
        git(url: 'git@github.org:fruitarmy/find3', branch: 'master')
      }
    }
  }
}