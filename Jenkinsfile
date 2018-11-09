pipeline {
  agent any
  stages {
    stage('Get') {
      steps {
        git(url: 'https://github.com/fruitarmy/find3', branch: 'jenkins')
      }
    }
  }
}
