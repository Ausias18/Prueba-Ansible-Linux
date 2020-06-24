pipeline {
  agent any
  
  stages {
        stage('Configure') {
       steps {
           sh 'pwd'
	   sh 'ansible-playbook -i inventory.yml apache-ansible.yml -vvv'
       	      }
     			}
         }
	 }
