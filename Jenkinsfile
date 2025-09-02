pipeline {
    agent { label 'host-agent' }  
	
    stages {
		stage('Create File') {
            steps {
                sh '''
		docker run -d --name nginx docker.arvancloud.ir/nginx
                '''
            }
        }
		}
        
    }


