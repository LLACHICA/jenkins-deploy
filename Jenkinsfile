pipeline {
  agent {
    label 'mediasrv'
  }
  stages {
    stage("Verify Tooling") {
      steps {
        sh '''
          sudo /usr/bin/docker info
          sudo /usr/bin/docker version
          sudo /usr/bin/docker compose version
        '''
      }
    }
  }
}
            

