pipeline {
    agent any
    stages {
        stage('Terraform_Installation') {
            steps {
                sh 'pwd'
                sh 'ls -latr'
                sh 'echo $USER'
                sh 'sh ./ansible.sh'
            }
        }
    }
}
