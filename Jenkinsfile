pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh "docker build -t yassineminsait2023/pokedex-flask:${env.BUILD_NUMBER} ."
      }
    }
  }
} 
