pipeline {
    agent {
        label 'ansible' 
    } 
    stages {
        stage('Run playbook') {
            steps {
                sh "docker run -dit --name nginx -p 85:80 nginx:latest"
            }
        }
    }   
}
