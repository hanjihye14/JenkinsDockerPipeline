node {
  stage('========== Clone repository ==========') {
    checkout scm
  }
  stage('========== Build image ==========') {
    app = docker.build("jenkins-docker-pipeline/my-image")
  }
 
}
