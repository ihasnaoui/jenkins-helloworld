node {
    // some block
	stage('clone') {
	    // some block
		git 'https://github.com/ihasnaoui/jenkins-helloworld'
	}
	stage('build') {
	    // some block
		sh label: '', script: '''javac Main.java
		'''	
	}
	stage('run') {
    	// some block
		sh label: '', script: '''java Main
		'''	
	}
}
