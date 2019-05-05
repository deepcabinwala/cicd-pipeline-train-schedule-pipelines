pipeline {
    agent any
    stages {
        stage('Buid') {
          steps {
            script {
              sh "./gradlew build"
            }
          }
        }
        stage('Archive') {
          steps {
            script {
              archiveArtifacts artifacts: 'dist/trainSchedule.zip'
              sh "cp dist/trainSchedule.zip /tmp"
            }
          }
        }
    }
}
