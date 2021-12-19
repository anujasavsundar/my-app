pipeline{
    agent any
    
    stages{
        stage("SCM"){
           git https://github.com/anujasavsundar/my-app.git
            
        }
            
        
        
        stage("Build"){
            sh 'mvn clean install'
            
        }
    }
}
