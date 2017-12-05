pipeline{
	agent any
    	stages {
		stage('Commit'){
			steps{
				sh 'git checkout demo'
				sh 'git pull'
			}	
		}
        	stage('Build'){
            		steps {
                		sh 'echo "Job Done"'
            		}	
        	}
	}
}
