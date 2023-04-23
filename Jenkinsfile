pipeline {
    agent any
    stages {
        stage('Run bash command') {
            steps {
                sh "ansible all -m ping"
            }
        }
    }   
}
