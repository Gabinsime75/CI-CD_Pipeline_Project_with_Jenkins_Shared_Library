pipeline {
  agent any
  stages {
    stage ('Git checkout') {
      steps {
        script {
          git branch: 'main', url: 'https://github.com/Gabinsime75/CI-CD_Pipeline_Project_with_Jenkins_Shared_Library.git'
        }
      }
    }
  }
}
