# my_taskwarrior_setup

# with ansible
`sudo apt install python-pip && pip install ansible && source ~/.profile`

# do the stuff

run the playbooks, inventory, etc to set up my taskwarrior and timewarrior setup.

before ... you may need to `sudo echo "just doing this so sudo login is saved"`

1. `ansible-playbook  taskwarrior_setup.yaml --connection=local -i hosts`
2. `ansible-playbook  timewarrior_setup.yaml --connection=local -i hosts`
3. `ansible-playbook taskwarrior_timewarrior_hook.yaml --connection=local -i hosts`

# TODO

- intheam setup
- make this into a role
- vagrant box or docker image with tests or just use travis
- Android compatibility with Termux (even possible?)
- NixOS compatibility

# Compatibility

Ubuntu
