


pipeline {
       agent{
           label {
                label "slave1"
            }
         }
       stages {
	       stage ('install_httpd') {
	                steps {
		               sh "sudo apt install apache2 -y"
		          }
		    }
           stage ('start httpd server') {
	                steps {
		               sh "sudo systemctl start apache2"
		            }
	        }
          stage ('status https') {
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
	  
