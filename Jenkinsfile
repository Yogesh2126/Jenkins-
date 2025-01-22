


pipeline {
        agent any 

	environment {
		   MAVEN_HOME = '/mnt/apache-maven-3.9.9'
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
