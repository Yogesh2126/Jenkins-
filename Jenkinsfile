


pipeline {
        agent any
	 tools {
		 maven 'Maven 3.8.1'
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
