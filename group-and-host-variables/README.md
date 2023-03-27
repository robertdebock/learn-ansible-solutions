# Group and host variables

These are solutions to the assignments described in the [group and host variables](https://robertdebock.nl/learn-ansible/ADVANCED/group_host_vars) chapter.

Create a group_vars directory.
Create a group_vars/all/ntp.yml file.
Set the ntp_server variable to 0.pool.ntp.org for all hosts.
Create a group_vars/switzerland/ntp.yml file.
Create a group_vars/netherlands/ntp.yml file.
Set the ntp_server variable to 0.ch.pool.ntp.org for all hosts in the switzerland group.
Set the ntp_server variable to 0.nl.pool.ntp.org for all hosts in the netherlands group.
