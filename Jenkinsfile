pipeline {
  agent any
  stages {
    stage('Etapa 1') {
      steps {
        echo 'Hola'
        bat 'mvn -v'
      }
    }
    stage('Sonar Analysis') {
      when (BRANCH_NAME == 'temp') {
        echo 'Excecuted only on temp branch.'
      }
    }    
    stage('Fin') {
        echo 'Fin'
    }    
  }
}
