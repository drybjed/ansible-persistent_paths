## [![DebOps](https://debops.org/images/debops-small.png)](https://debops.org) persistent_paths

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![Travis CI](https://img.shields.io/travis/debops/ansible-persistent_paths.svg?style=flat)](https://travis-ci.org/debops/ansible-persistent_paths)
[![test-suite](https://img.shields.io/badge/test--suite-ansible--persistent__paths-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-persistent_paths/)
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-debops.persistent_paths-660198.svg?style=flat)](https://galaxy.ansible.com/ypid/persistent_paths)


This role provides a generic mechanism to declare which files/directories
are required to be persistent. How this information is used can then be defined in
this role. The main use case of this role is the use as dependency role.
The role was written to allow to configure TemplateBasedVM AppVMs on [Qubes OS][].

Supports:

* [Qubes OS][] R3.2 and later using [bind-dirs][]

[Qubes OS]: https://www.qubes-os.org/
[bind-dirs]: https://www.qubes-os.org/doc/bind-dirs/

### Installation

This role requires at least Ansible `v2.1.4`. To install it, run:

```Shell
ansible-galaxy install debops.persistent_paths
```

### Documentation

More information about `debops.persistent_paths` can be found in the
[official debops.persistent_paths documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-persistent_paths/docs/).



### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://debops.org/) for a complete solution to run your Debian-based infrastructure.





### Authors and license

- [Robin Schneider](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-ypid) (maintainer) | [e-mail](mailto:ypid@riseup.net) | [GitHub](https://github.com/ypid)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of [DebOps](https://debops.org/). README generated by [ansigenome](https://github.com/nickjj/ansigenome/).