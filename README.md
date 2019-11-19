# create username and password, update public key ssh for users
command run deploy:
ansible-playbook -i deploy_hosts deploy_authorized_keys.yml
