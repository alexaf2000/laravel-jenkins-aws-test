pipeline {
  agent any
  stages {
    stage('Test code quality') {
      environment {
        Test = 'toast'
        MYSQL_USER = 'root'
      }
      steps {
        echo 'Code quality pass'
      }
    }

    stage('Unit tests') {
      steps {
        echo 'Unit test pass'
      }
    }

    stage('Manual test') {
      steps {
        input(message: 'Allow production deployment', id: 'allow', ok: 'allow', submitter: 'allow', submitterParameter: 'allow')
      }
    }

    stage('Deploy Production') {
      steps {
        echo 'Deployed successfuly'
      }
    }

  }
}