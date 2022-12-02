pipeline {
  agent {
    label 'jenkins-slave'
  }
  
  stages {
    stage('Build') {
      when {
            tag "release-*"
      }
      
      steps {
        echo 'Hello World building Tag'
      }
    }
  }
}
