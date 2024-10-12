pipeline {
  agent any
  tools {
    maven 'maven3'
  }
  stages{
    stage('git checkout'){
      steps{
      git 'https://github.com/Lokeshmovietalks/my-app.git'
      }
    }
    stage('Maven Build'){
      steps{
      sh 'mvn clean package'
      }
    }
  }
  
}
