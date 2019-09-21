pipeline {
 	agent any
 	stages {
	  stage ('compile stage') {

		steps {
 		  withmaven(maven : 'maven_3_5_0') {
		    sh 'mvn clean complete
 		   }
              }
   }
	stage ('testing stage') {
		steps {
 		  withmaven(maven : 'maven_3_5_0') {
		    sh 'mvn test
 		   }
              }
   }

	stage ('deployment stage') {
 		steps {
 		  withmaven(maven : 'maven_3_5_0') {
		    sh 'mvn clean complete
 		   }
              }
   }

}

}
