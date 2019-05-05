node {
  stage('Buid') {
    step {
      script {
        sh "./gradlew build"
      }
    }
  }
  stage('Archive') {
    step {
      script {
        sh "cp dist/trainSchedule.zip /tmp"
      }
    }
  }
}
