pipeline{
    agent any
    stages{
        stage('Ansible Playbook '){
            steps('Running Ansible playbook'){
                
            ansiblePlaybook(
                installation: 'ansible',
                playbook: //playbook path
                inventory: 'localhost',
                vaultCredentialsId: 'vault_pass',
                colorized: true
            )

            }
        }
    }
}