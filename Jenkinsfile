


pipeline {
        agent any
	 tools {
		 maven 'maven'
	 }

	     stages {
		         stage (' maven validate') {
				     steps {
					       sh 'mvn validate'
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
