pipeline{
    agent{label 'Linux'}
    stages{
        stage('checking git '){
            steps{
             git clone 'https://github.com/Manikanta937/Ansible_Jenkins.git'
            }
        }
        stage('executing playbook'){
          steps{
            sh 'ansible -i inventory.ini all playbook.yml '
    }
}
}
}
