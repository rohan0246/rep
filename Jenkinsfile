pipeline {
    agent any 
    stages {
    stage('mav install') {
      steps {
          withmaven(maven: 'mav'){
        sh 'mvn clean install'

      }
    }

  }
}
}
