pipeline {
  agent any 
  parameters {
    string(name: 'release', description: 'Tag to be applied to release')
  }
  stages {
    stage('Example') {
      steps {
        script {
          input.hasPermissionsDeploy()
        }
      }
    }
  }
}