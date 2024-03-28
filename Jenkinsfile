node ('local') {
    try {

//------------------------------------------------------Code-Clone-----------------------------------------------------------------//

  stage 'Cloning Git'
  url:'https://github.com/yadavprakash/jenkins.git', branch:'master'

//--------------------------ansiblePlaybook run ------------

  stage 'run ansible'
   wget 'ansible-playbook ansible/test.yml'


// pipeline {
//     agent any
//
//     stages {
//         stage('Checkout') {
//             steps {
//                 // Checkout code from Git repository
//                 git 'https://github.com/yadavprakash/jenkins.git'
//             }
//         }
//         stage('Install Ansible') {
//             steps {
//                 // Install Ansible
//                 sh 'pip install ansible'
//             }
//         }
//         stage('Run Ansible Playbook') {
//             steps {
//                 // Run Ansible playbook
//                 ansiblePlaybook(
//                     playbook: 'ansible/test.yml',
//                     inventory: 'ansible/inventory/hosts.ini',
//                 )
//             }
//         }
//     }
// }
