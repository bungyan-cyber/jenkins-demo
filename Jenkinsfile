pipeline {


  agent { label 'kubepod' }
  

  stages {
   
     stage('Checkout Source') {
      steps {
        git 'https://github.com/bungyan-cyber/jenkins-demo.git'
      }
    }
  }
}
    
