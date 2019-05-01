node {
stage('Checkout') {
        checkout scm
    }
stage('RUN') {

  ansiblePlaybook(
            playbook: 'playbook.yml',
            inventory: 'inventory.ini',
            credentialsId: 'ansible_jenkins')
         

}
stage('Finishing') {
}
}
