# my_taskwarrior_setup

Ansible playbooks, inventory, etc to set up my taskwarrior and timewarrior setup.

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
