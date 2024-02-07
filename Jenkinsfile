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
      when {
        branch 'temp'
      }
      steps{
        echo "temp"
      }
    }    
    stage('Fin') {
      steps{
        echo 'Fin'
      }
    }    
  }
}
