pipeline {
    agent {
        label 'ansible' 
    } 
    stages {
        stage('Run playbook') {
            steps {
                sh "ansible-playbook playbook.yaml -i hosts_git"
            }
        }
    }   
}
