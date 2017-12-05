pipeline{
	agent any
    	stages {
		stage('Commit'){
			steps{
				sh 'git checkout demo'
				sh 'git tag -am demo "changes"'
				sh 'git push git@github.com:buddipn/jenkins-test.git demo'
				}
		}
        	stage('Build'){
            		steps {
                		sh 'echo "Job Done"'
            		}	
        	}
	}
}
