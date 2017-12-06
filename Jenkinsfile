pipeline {
    agent any
    parameters{
        string(name: 'USER', defaultValue: 'buddipn', description: 'Who are you?')
        booleanParam(name: 'BUILD', defaultValue: true, description: 'Runs the job')
        choice(name: 'JOB', choices: 'Design\nDevelopment\nTest', description: 'What job to run?')
    }
    stages {
        stage('Options') {
            steps {
                sh 'echo "Select from the following options:"'
                sh 'echo ${params.USER}'
                sh 'echo ${params.BUILD}'
                sh 'echo ${params.JOB}'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Hello ${USER}"'
            }
        }
    }
}

