#!/usr/bin/env groovy
properties([
    [$class: 'GithubProjectProperty',
    displayName: '',
    projectUrlStr: 'https://github.com/buddipn/jenkins-test.git'],
    pipelineTriggers([githubPush()])])
pipeline{
	agent any
    	stages {
        	stage('Build'){
            		steps {
                		sh 'ls'
            		}	
        	}
		stage('Result'){
            		steps {
                		sh 'echo "Job Done"'
            		}	
        	}
	}
}
