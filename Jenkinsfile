pipeline{
    agent any
    stages {
       stage("Git Checkout"){
           steps {"Git Checkout"} {
            git credentialsId: 'github', url: "https://github.com/Vaheguru/pipeline.git"
           }              
         }
       } 
    }
  
