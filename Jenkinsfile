pipeline {
  agent {
    label 'mediasrv'
  }
  stages {
    stage("Verify Tooling") {
      steps {
        sh '''
          docker info
          docker version
          docker compose version
          curl --version
          jq --version
        '''
      }
    }
  }
}
            

