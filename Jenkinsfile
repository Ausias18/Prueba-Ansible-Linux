pipeline {
  agent any
  
  stages {
        stage('Configure') {
       steps {
           sh 'pwd'
	   sh 'sudo yum install python2'
	   sh 'ansible-playbook -i inventory.yml apache-ansible.yml -vvv -C -e ansible_python_interpreter=/usr/bin/python2.7'
       	      }
     			}
         }
	 }
