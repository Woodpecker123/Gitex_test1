pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        writeFile(file: 'Sample.txt', text: 'Hello There')
      }
    }

    stage('test2') {
      steps {
        echo 'Hello'
      }
    }

  }
}