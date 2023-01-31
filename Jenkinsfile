@Library('piper-lib-os') _

node() {
  stage('init') {
    deleteDir()
    checkout scm
  }
  
  stage('integrationArtifactTransport Command') {
       integrationArtifactTransport script: this
  }
}
