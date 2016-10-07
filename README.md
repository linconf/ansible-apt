# Ansible Role: apt

An Ansible role that configures and manages APT on Debian/Ubuntu systems.

This role is a fork of [`debops.ansible-apt`](https://github.com/debops/ansible-ferm),
an excellent role created and maintained as part of the [DebOps Project](https://debops.org).

## Role Modifications

**Additional role variables:**

- `apt_packages: []` - Install apt packages by role, host or group
- `apt_host_packages: []`
- `apt_group_packages: []`
- `apt_remove_packages: []` - Remove apt packages by role, host or group
- `apt_remove_host_packages: []`
- `apt_remove_group_packages: []`


## Author and License

Original Author: [Maciej Delmanowski](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-drybjed) | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

Original Author: [Robin Schneider](https://docs.debops.org/en/latest/debops-keyring/docs/entities.html#debops-keyring-entity-ypid) | [e-mail](mailto:ypid@riseup.net) | [Twitter](https://twitter.com/ypid) | [GitHub](https://github.com/ypid)

This fork is maintained by Chad Sheets - [GitHub](https://github.com/cjsheets) | [Blog](http://chadsheets.com/) | [Email](mailto:chad@linconf.com)

License: [GPL-3.0](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

[![Analytics](https://cjs-beacon.appspot.com/UA-10006093-3/github/linconf/ansible-apt?pixel)](https://github.com/linconf/ansible-apt)
