pipeline {
  agent any
  stages {
    stage('Etapa 1') {
      agent any
      steps {
        echo 'Hola'
        tool(name: 'MAVEN_3_8_6', type: 'maven')
        tool(name: 'JDK_11', type: 'jdk')
      }
    }

  }
}