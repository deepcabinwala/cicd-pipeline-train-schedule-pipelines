stage('Buid') {
  script {
    step {
      sh "./gradlew build"
    }
  }
}
stage('Archive') {
  script {
    step {
      sh "cp dist/trainSchedule.zip /tmp"
    }
  }
}
