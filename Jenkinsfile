// commit
pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
	stage('Test2') {
	    steps {
		echo 'test'
	    }
    }
}
