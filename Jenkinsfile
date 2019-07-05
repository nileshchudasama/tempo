pipeline{	
	agent any
		stages{
			stage('Check connections'){
			steps{
                          sh 'ansible -m ping test2'
			}
                        }
			stage('Create nginx in docker'){
			steps{
                          sh 'ansible-playbook test_servers.yml'
			}
                        }
                }
}

