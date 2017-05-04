pipeline {
  agent any
  stages {
    stage('Print Message') {
      steps {
        echo 'Test'
      }
    }
    stage('Pep8') {
      steps {
        sh 'pep8 app.py > pep8report.txt'
      }
    }
  }
}