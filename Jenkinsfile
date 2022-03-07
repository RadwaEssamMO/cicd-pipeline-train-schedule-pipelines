pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation goodbay 2'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
