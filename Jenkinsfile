pipeline{
agent any
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
    }

}
