pipeline {

    agent any
    stages {
    
    	stage('Build') {
    	    steps {
    		echo 'Running build automation'
    		sh './mvn package'
    		archiveArtifacts artifacts: 'target/*.jar'
    	    }
    	}
    
    }
}