# Windows Ansible certificate-based authentication
These scripts and configs help setup the ansible server to communicate to the windows host via WinRM, for the Windows client installation is on this [documentation].

# To test the connectivity
* `cd windows-ansible-script`

* `ansible -i all_hosts.txt win -m win_ping`

# Future improvement
* Create a short script that will update the `all_hosts.txt` file according to Centreon alerts.
* Add VM tagging, so we can execute only to a specific tag.

