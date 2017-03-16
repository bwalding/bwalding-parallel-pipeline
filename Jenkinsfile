//A comment
node() {

  stage('checkout') {
  }

  stage('test') {
  }

  stage('build') {
    parallel (
     "linux"   : { },
     "darwin"  : { },
     "windows" : { },
    )
  }

  stage('deploy') {
  }

  stage('notify') {
  }

}
