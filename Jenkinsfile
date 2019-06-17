pipeline{
		
		agent any
		
		stages{
			
			stage('Build'){
				steps{
					echo 'build stage'
					sh 'mvn clean compile'
				}
					
				
			}
			stage('Deployments'){
				steps {
					echo 'deploying to staging'
					
				}
			}
		}
	}
