pipeline {
    agent { label 'host-agent' }  
	triggers {
        githubPush()               // trigger on GitHub push events
    }
    stages {
		stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/alibahrami2/jenkins_pipline.git'
            }
		}
        
    }
}

