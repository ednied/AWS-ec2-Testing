pipeline {
    agent any

    stages {

        stage('Run Ansible Playbook') {
            steps {
                sh 'ansible-playbook new_user.yml'
            }
        }

    }
}
