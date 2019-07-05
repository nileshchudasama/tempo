1. dir:nginx - is a ansible role to create nginx container in docker on host machine
2. test_servers.yml - is a playbook file 
3. Jenkinsfile - is pipeline syntax , build by jenkins pipeline


Step -1
 - open jenkins

Step-2
 - create new pipline
 - in general -> select "GitHub project" -> set pojecturl "https://github.com/nileshchudasama/tempo.git"
 - in Pipeline -> select definition "pipeline script from SCM" -> choose SCM "Git"  
               -> give Repository URL "https://github.com/nileshchudasama/tempo.git"
               -> select script path "Jenkinsfile"
 - apply and save
 
 Step-3
 now build job
 
 
