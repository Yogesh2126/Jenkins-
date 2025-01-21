pipeline {
  agent any 
     stages {
	       stage ('install-httpd') {
	                steps {
		               sh "sudo apt install apache2 -y"
		          }
		    }
           stage ('start httpd') {
	                steps {
		               sh "sudo systemctl start apache2"
		            }
	        }
          stage ('httpd status') {
	                steps{
	                  sh "sudo systemctl status apache2"
	                }
	        }
          stage ('index html') {
	                steps {
					 echo "Hey all"
		               //echo "hey all $(hostname)">>  /var/www/http/index.html 
	                }
	            }
	    }
 }
	  
	  
