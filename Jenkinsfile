pipeline{
    agent any
    
    stages{
        stage("SCM"){
            steps{
               git clone https://github.com/anujasavsundar/my-app.git
            }
            
        }
        
        stage("Build"){
            steps{
                sh 'mvn clean install'
            }
        }
    }
}
