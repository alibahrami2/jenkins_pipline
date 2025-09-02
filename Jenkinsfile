pipeline {
    agent { label 'host-agent' }   // ensure this runs on your host agent
    stages {
        stage('Create File') {
            steps {
                sh '''
		docker run -d -name nginx docker.arvancloud.ir/nginx
                '''
            }
        }
    }
}

