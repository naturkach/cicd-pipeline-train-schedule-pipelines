pipeline {
  agent any
  stages {
    stage ('Build') {
      steps {
        echo 'Running build automation'
        sh './gradlew build --no-demon'
        archiveArtifacts: 'dist/test.zip'        
      }
    }    
  }
}
