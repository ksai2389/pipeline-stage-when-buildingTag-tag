pipeline {
  agent {
    label 'jenkins-slave'
  }
  
  stages {
    stage('Build') {
      when {
            buildingTag()
      }
      
      steps {
        echo 'Hello World building Tag'
      }
    }
  }
}
