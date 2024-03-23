pipeline {
    agent any

    stages {
        stage('clone project') {
            steps {
		sh 'rm -rf timesheet-devops'
                sh 'git clone https://github.com/mhassini/timesheet-devops'
            }
        }
	stage('build') {
            steps {
                sh 'mvn clean install -X'
            }
        }
        
       
        
    }
}
