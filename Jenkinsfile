pipeline {
  agent any
  stages {
    stage('Print something') {
      environment {
        Test = 'toast'
        MYSQL_USER = 'root'
      }
      steps {
        echo 'All is correct?'
      }
    }

  }
}