pipeline{
	agent any
	stages{
		stage("GIT"){
		 git https://github.com/anujasavsundar/my-app.git
		}
		
		stage("Maven"){
		 sh 'mvn clean install'
		}
	}
}
