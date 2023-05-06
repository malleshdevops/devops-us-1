pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            sh 'echo "stage1"'
          }
        }

        stage('stage2') {
          steps {
            sh 'echo "stage2"'
          }
        }

      }
    }

    stage('stage3') {
      steps {
        sh 'echo "stage3"'
        echo 'stage3'
      }
    }

    stage('stage4') {
      steps {
        sh 'echo "stage4"'
      }
    }

  }
}