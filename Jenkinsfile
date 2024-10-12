pipeline {
  agent any
  tools {
    maven 'maven3'
  }
  stages{
    stage('git checkout'){
      git 'https://github.com/Lokeshmovietalks/my-app.git'
    }
    stage('Maven Build'){
      sh 'mvn clean package'
    }
  }
  
}
