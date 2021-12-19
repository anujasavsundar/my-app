pipeline{
    agent any
    
    stages{
        stage("SCM"){
            steps{
               git https://github.com/anujasavsundar/my-app.git
            }
        }
            
        
        
        stage("Build"){
            steps{
                sh 'mvn clean install'
            }
        }
    }
}
