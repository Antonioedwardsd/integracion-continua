pipeline {
  agent any
  stages {
    stage('Clonar Repo') {
      steps {
        git url: 'https://github.com/Antonioedwardsd/integracion-continua.git', branch: 'master'
      }
    }
    stage('Instalar Dependencias') {
      steps {
        sh 'npm install' // Cambia de 'npm ci' a 'npm install'
      }
    }
    stage('Pruebas') {
      steps {
        sh 'npm run test'
      }
    }
  }
}
