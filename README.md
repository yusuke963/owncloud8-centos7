# owncloud8-centos7
Install ownCloud8 on CentOS7

#Requirements
Ansible 1.4 or higher and platform.

#System Requirements
CentOS7.x Minimal Install

#How to install Ansible<br>
 (1) yum install -y git epel-release<br>
 (2) yum makecache<br>
 (3) yum install -y ansible git<br>
 (4) git clone [GitHub URL]<br>
 (5) ansible-playbook -i host install.yml
