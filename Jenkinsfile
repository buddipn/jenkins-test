pipeline{
	agent any
    	stages {
		stage('Commit'){
			steps{
				//withCredentials([usernamePassword(credentialsId: 'f44b0096-0c33-4458-98e5-b89447bf4946', usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD')]){
				sh 'git checkout demo'
				sh 'git pull'
				sh 'git push git@github.com:buddipn/jenkins-test.git'
				}	
			}
		}
        	stage('Build'){
            		steps {
                		sh 'echo "Job Done"'
            		}	
        	}
	}
}
