# Set up Linux

My Ansible config for setting up Linux (Debian) machines.

To set up a new machine, you need to install ansible first.

    sudo apt-get update && sudo apt-get upgrade
    sudo apt-get -y install ansible git curl

Then clone the repository and run a playbook.

To run a playbook, for example:

    ansible-playbook playbooks/wsl-ubuntu-setup.yml -K

The ```-K``` is to prompt for sudo password.

