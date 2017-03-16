//A comment
node() {

  stage('checkout') {
    checkout scm
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
