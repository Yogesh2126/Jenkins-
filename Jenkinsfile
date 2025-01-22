


pipeline {
        agent any
	 tools {
		 maven 'maven'
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
