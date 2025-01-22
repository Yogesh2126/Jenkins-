


pipeline {
        agent any
	 tools {
		 maven 'Maven 3.9.9'
	 }

	     stages {
		         stage ('comple') {
				     steps {
					       sh 'mvn comiple'
						}
				    }
				stage ('test') {
				        steps {
						   sh 'mvn test'
						}
					}	
				stage ('clean package') {
				     steps {
					     sh 'mvn clean package'
					 }
				}
		   }
 }
