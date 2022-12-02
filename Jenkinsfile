pipeline {
  agent {
    label 'jenkins-slave'
  }
  
  stages {
    stage('Build') {
      when {
            tag "2.0"
      }
      
      steps {
        echo 'Hello World building Tag'
      }
    }
  }
}
