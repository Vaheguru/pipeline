pipeline{
    agent any
    stages {
       stage("Git Checkout"){
           steps {"Git Checkout"} {
            git credentialsID: 'github', url: "https://github.com/Vaheguru/pipeline.git"
           }              
         }
       } 
    }
  
