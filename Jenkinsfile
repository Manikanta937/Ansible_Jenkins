pipeline{
    agent{label 'Linux'}
    stages{
        stage('checking git '){
            steps{
             git credentialsId: 'ac04981c-9f60-4750-b0d7-466f465e6780', url: 'https://github.com/Manikanta937/Ansible_Jenkins.git'
            }
        }
        stage('executing playbook'){
          steps{
            sh 'ansible-playbook -i inventory.ini playbook.yml '
    }
}
}
}
