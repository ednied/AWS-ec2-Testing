pipeline {
    agent any

    parameters {
        choice(
            name: 'PLAYBOOK',
            choices: [
                'playbook1.yml',
                'user_create.yml'
            ],
            description: 'Select the Ansible playbook to run'
        )
    }

    stages {
        stage('Run Ansible Playbook') {
            steps {
                sh "ansible-playbook ${params.PLAYBOOK}"
            }
        }
    }
}
