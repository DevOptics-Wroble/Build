
// Jenkinsfile scripted pipeline
	node {
	    stage ('checkout') {
	        checkout scm
	    }
	    stage ('produce') {
	        // Notify DevOptics that this run produced plugin-a.txt.
	        gateProducesArtifact file: 'plugin-0130.txt'
	          sh 'sleep 30'
	    }       
	}
