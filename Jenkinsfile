pipeline{
	agent any
	tools {
        maven 'apache-maven-3.8.6' 
    }
	stages{
	/*
		stage('SCM - Checkout'){
			steps{
				git url: 'https://github.com/javahometech/myweb'
			
			}
		}
	*/	

				
				stage('Maven Build'){
					steps{
					
						sh "mvn clean package"
					}
				
				}
			
			}
		
		}	
	

	
