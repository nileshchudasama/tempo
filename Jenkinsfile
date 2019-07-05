pipeline{	
	agent any
		stages{
			stage('Check connections'){
                          sh 'ansible -m ping test2'
                        }
			stage('Create nginx in docker'){
                          sh 'ansible-playbook test_servers.yml'
                        }
                }
}

