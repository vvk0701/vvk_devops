Instantiate 2 Instance on AWS

1)Jenkins Server
2)Node where Webapp will be installed
3)Open 8080 on AWS Explicitlyby default only 80 is opened but jenkins is installed on 8080
4)Install Ansible on Jenkins Server
5)Install Ansible Plugin on Jenkins Server
6)Copy Public Key of Jenkins Server to Node1 & Verify SSH to Node from Master
7)Install Tomcat on Node1
8)Install maven on Node1
9)Create a Ansible Playbook for Packaging Webapp, Copying to Tomcat, Restarting Tomcat
10)Create a jenkins job to invoke Ansible play book
