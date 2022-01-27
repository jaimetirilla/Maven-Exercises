pipeline {
  agent any
  stages {
    stage('mensaje') {
      steps {
        echo 'Compilacion iniciada'
      }
    }

    stage('Cambio de rama') {
      parallel {
        stage('Cambio de rama') {
          steps {
            sh 'git checkout answer4'
          }
        }

        stage('TEXTO') {
          steps {
            echo 'Cambiando de rama'
          }
        }

      }
    }

    stage('Compilacion') {
      steps {
        sh 'mvn clean install'
        echo 'CHACHI'
      }
    }

  }
}