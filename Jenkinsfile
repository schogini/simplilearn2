pipeline {	 
	agent any	 
    	stages {     	 
    	stage("Compile") {          	 
            	steps {               	 
                	sh "mvn compile"          	 
            	}     	 
        	}     	 
    	stage("Unit test") {          	 
        	steps {               	 
                	sh "mvn test"          	 
            	      }     	 
        	}	 
      	stage("Function test by Rakesh") {          	 
        	steps {               	 
                	echo "Rakesh testing"          	 
            	      }     	 
        	}  	
    	stage("Extra test") {          	 
        	steps {               	 
                	echo "Extra test"          	 
            	}     	 
        		 
    	}
	}
}


