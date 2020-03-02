pipeline {

    agent any
    stages {
    
    	stage('Building spring-petclinic...') {
    	    steps {
    		echo 'Running build automation'
    		sh 'mvn package'
    		archiveArtifacts artifacts: 'target/*.jar'
    	    }
    	}
    
    }
}