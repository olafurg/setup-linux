# Set up Linux

My Ansible config for setting up Linux (Debian) machines.

To set up a new machine, clone the repository and run the preparation script.

    chmod +x prepare.sh
    ./prepare.sh

To run a playbook, for example:

    ansible-playbook playbooks/wsl-ubuntu-setup.yml -K

The ```-K``` is to prompt for sudo password.
