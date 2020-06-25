pipeline {
  agent any
  
  stages {
        stage('Configure') {
       steps {
           sh 'pwd'
	   sh 'ansible-playbook -i inventory.yml apache-ansible.yml -e "ansible_python_interpreter=/usr/bin/python2" -vvv'
       	      }
     			}
         }
	 }
