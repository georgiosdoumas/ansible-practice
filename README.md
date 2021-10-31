# ansible-practice
All subfolders and files under the ansible-practise should exist on your ansible server (under /etc/ansible, and an ssh connection to the remote Ubuntu VM must be available.
Execute the following command on the ansible server (WARNING: no test has been conducted, so nothing is guaranteed to work): 

ansible-playbook -i hosts site.yml
