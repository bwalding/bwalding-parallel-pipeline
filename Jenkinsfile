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
    sh "echo lol"
  }

  stage('notify') {
  }

}
