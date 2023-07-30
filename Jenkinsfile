pipeline {


  agent { label 'kubepod' }
  

  stages {
   
     stage('Checkout Source') {
      steps {
        git 'https://github.com/justmeandopensource/playjenkins.git'
      }
    }
  }
}
    
