pipeline {
  agent any
  stages {
    stage('mensaje') {
      steps {
        echo 'Iniciando Compilaci�n'
        echo 'Compilacion finalizada'
        sh 'mvn clean install'
      }
    }

  }
}