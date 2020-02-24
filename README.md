# ansible-roles-apache-httpd
Install apache httpd on AWS Dynamic EC2 Instances using Tag as the Inventory.

To Run this module you need to have the ec2.py and ec2.ini configured on your local machine. 
Also the AWS profile is configured and the private keypair is also need to be configured

The AWS EC2 machines must be tagged with Key:Ansible and Value:Slave.

How to Run
ansible-palybook site.yaml
