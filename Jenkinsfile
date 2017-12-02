pipeline {
    agent { docker { image 'dockerkriish/jenkins-docker-slave:latest' } 
          }
    stages {
	    
        stage('build') {
            steps {
                sh 'mvn --version'
		sh "echo venkatesh"
                sh "echo jagathpathi"
            }
        }
    }
}

