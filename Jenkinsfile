pipeline{
	agent any
    	stages {
		stage('Commit'){
			steps{
				sh 'git checkout demo'
			}	
		}
        	stage('Build'){
            		steps {
                		sh 'echo "Job Done"'
            		}	
        	}
	}
}
