pipeline {

  agent any
  stages {

    stage ('Build') {
    
      steps {
        echo 'Runninhg build automation'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
