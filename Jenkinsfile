pipeline {
    agent any

    stages {

        stage('Run Ansible Playbook') {
            steps {
                sh 'ansible-playbook user_create.yml'
            }
        }

    }
}
