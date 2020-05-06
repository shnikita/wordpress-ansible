pipeline {
  agent {
    dockerfile {
      filename 'test'
    }

  }
  stages {
    stage('error') {
      steps {
        mail(subject: 'df', body: 'dfd', bcc: 'df', cc: 'vc')
      }
    }

  }
}