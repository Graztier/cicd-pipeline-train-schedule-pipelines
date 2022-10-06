pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'text' 
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts 'dist/trainSchedule.zip'
      }
    }
  }
}
