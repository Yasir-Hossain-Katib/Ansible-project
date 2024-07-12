# Ansible-project

This is an Ansible project where I have created 4 EC2 instances on AWS. Here 1 is Ansible master and other 3 are nodes. So I write a playbook to manage passwordless authentication with the master server so that I can configure the other 3 node servers. And I installed nginx server on the 3 nodes with the master server using ansible playbooks and also deploy the index.html file there. So now we can visit the /var/www/html/index.html through those node servers IPV4 public addresses.
