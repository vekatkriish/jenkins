pipeline {
    agent { docker { image 'maven:3.3.3' } 
          }
    environment{

               CC = 'clang'

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

