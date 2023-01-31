# What

Sets up a Debian host the way I like it for desktop use.

# How to Use

Immediately after installing a Debian host change the `hosts` file to reflect the IP address, then use `ansible-playbook ./playbook.yml --ask-become-pass --ask-pass` to setup the other packages.  After the first run, later runs should not need the `--ask-pass` because the first will have installed the ssh authorized key.
