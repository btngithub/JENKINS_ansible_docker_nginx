pipeline {
    agent {
        label 'ansible' 
    } 
    stages {
        stage('Run bash command') {
            steps {
                sh "ansible all -m ping"
            }
        }
    }   
}
