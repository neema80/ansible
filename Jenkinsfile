pipeline {
    agent any
    stages {
        stage('Test Ansible Playbook') {
            steps{
                ansiblePlaybook colorized: false, disableHostKeyChecking: true, forks: 1, installation: 'Ansible', inventory: 'hosts', playbook: 'final.yaml'
            }   
        }
    }
}
