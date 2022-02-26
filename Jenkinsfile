pipeline {
 
agent { node { label 'Linux-Demo' } }
stages {
     stage('Run Ansible playbook') {
            steps {
                sh 'ansiblePlaybook extras: 'hosts=webservers', inventory: 'lab.ini', playbook: 'deploy.yml''
            }
        }
        
    }
}
