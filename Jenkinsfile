pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''ls
./gradlew -clean testDevelopDebugUnitTest'''
      }
    }
  }
}