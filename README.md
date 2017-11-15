ansible-role-motd
======

This role will sync configs from a given source directory over to the target host's /etc/update-motd.d/ directory.


things to know
-----

The files you create in "Role_MOTD_cfg_dir" should be 0755 and begin with `#!/bin/sh`

Filenames must follow this format (where NN is the 2-digit # corresonding to its place): `NN-xxxxxxxx` or `NN-xxxxxx-xxxxx`.  They should not contain any underscores or uppercase (only 2 leading digits, followed by `-` and lowercase)


Author Information
-----

abarrett@globeandmail.com
