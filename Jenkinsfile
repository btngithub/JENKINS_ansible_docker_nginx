pipeline {
    agent {
        label 'ansible' 
    } 
    stages {  
        stage('Run playbook') {
            steps {
                sh "ansible-playbook 192.168.1.11 -i /etc/ansible/hosts playbook.yaml"
            }
        }
    }   
}
