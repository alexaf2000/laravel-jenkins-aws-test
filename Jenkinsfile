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

    stage('') {
      steps {
        input(message: 'Does it works well on that\'', id: 'works', ok: 'Yes, it works', submitter: 'Don\'t know', submitterParameter: 'yes')
      }
    }

  }
}