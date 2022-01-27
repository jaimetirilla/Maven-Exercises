pipeline {
  agent any
  stages {
    stage('mensaje') {
      steps {
        echo 'Iniciando Compilación'
        echo 'Compilacion finalizada'
        sh 'mvn clean install'
      }
    }

  }
}