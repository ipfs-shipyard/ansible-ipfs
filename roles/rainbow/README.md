Ansible role for Rainbow
========================

This is the Ansible role to deploy Rainbow: a high performant IPFS HTTP gateway.


Requirements
------------

Nothing special.

Role Variables
--------------

  - `rainbow_seed`: set an identity seed for all hosts (same one for all, group variable)
  - `rainbow_seed_index`: each host needs a unique index (host variable)
  - `rainbow_version`: Git branch, tag or commit to install.

Dependencies
------------

None.

Example Playbook
----------------

Example:

    - hosts: servers
      roles:
	    - role: ipfs.rainbow
		  become: true

License
-------

MIT

Author Information
------------------

@hsanjuan
