# Shopizer-QT-Ansible

This ansible playbook helps deploying Shopizer on a tomcat server from a Debian and redhat machine installation.
To run 
a. Take checkout of the code and place it on home/username directory
b. Once playbook is run, The war file would automatically downloaded from the server
c. The inventory for this project is stored in roles/shopizer/test/inventory. Edit this accordingly
d. Type the following command on ACS

i. cd ~
ii. ansible-playbook -i roles/shopizer/tests/inventory shopizer.yml

To access Shopizer: Open browser and enter following url: http:public_ip/8080/ROOT
