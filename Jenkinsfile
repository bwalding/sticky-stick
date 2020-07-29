pipeline {
  
  options {
    timestamps()
    timeout(time: 30, unit: 'MINUTES')
  }

  stages {
    stage('Stage 1') {
      steps {
        script {
            print "All ok in stage 1"
        }
      }
    }

    stage('Stage 2') {
      steps {
        script {
            exit 2
        }
      }
    }
  }
}