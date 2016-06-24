Papyros Server Provisioning
===========================

This provides Ansible provisioning for the Papyros build server.

### Features

 * Daily OSTree builds of a Arch-based GNOME OS
 * Hosted OSTree repo at http://build.papyros.io/ostree

### Missing features

 * Build server for packages and ISOs
 * The Lounge IRC hosting

### Usage

To deploy:

    ansible-playbook -i inventory playbook.yml
