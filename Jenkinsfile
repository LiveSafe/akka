pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''files = sh (script: \'ls -l\',
                returnStdout: true).trim()
echo "${files}"
./gradlew -clean testDevelopDebugUnitTest'''
      }
    }
  }
}