pipeline{
node
    stages {
	stage('Checkout'){
		steps{
			sh 'git checkout demo'
		}
	}
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
            }
        }
	stage('test'){
		steps{
			sh 'echo "This build deploys the Jenkinsfile in demo branch"
		}
    }
}
}
