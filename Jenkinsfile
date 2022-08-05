pipeline{
	agent any
	tools { 
           maven 'M2_HOME' 
           jdk 'JAVA_HOME' 
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
	

	
