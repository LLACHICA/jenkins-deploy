pipeline {
  agent {
    label 'mediasrv'
  }
  stages {
    stage("Verify Tooling") {
      steps {
        sh '''
          /usr/bin/docker info
          /usr/bin/docker version
          /usr/bin/docker compose version
        '''
      }
    }
  }
}
            

