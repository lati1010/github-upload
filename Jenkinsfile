pipeline {
    agent any
    stages {
        stage('Terraform_Installation') {
            steps {
                sh 'pwd'
                sh 'ls -lahtr'
                sh 'chown -R root:root var/lib/jenkins'
                sh 'chmod +x ansible.sh'
                sh 'sh ./ansible.sh'
            }
        }
    }
}
