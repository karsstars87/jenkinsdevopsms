//SCRIPTED
//DECLARATIVE
pipeline {
	 agent any
	 stages {
		 stage('Build') {
			 steps {
                echo "Build"
	            echo "Test"
	            echo "Integration Test"
			 }
		 }
		 stage('Test') {
			 steps {
	            echo "Test"
			 }	
	     }
	 stage('Integration') {
			 steps {
                echo "Integration Test"
			 }
	    }
	 }	
	  
	 post {
		 always {
			 echo 'im awesome. i run always'
		 }
		 success {
			 echo 'I run when you are successful'
		 }
		 failure {
			 echo "i run when you fail"
		 }
	 }
}	 	 