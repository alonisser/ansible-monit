## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) monit

[![Travis CI](http://img.shields.io/travis/debops/ansible-monit.svg?style=flat)](http://travis-ci.org/debops/ansible-monit) [![test-suite](http://img.shields.io/badge/test--suite-ansible--monit-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-monit/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.monit-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/1575)

`debops.monit` role allows you to install and configure
[Monit](http://mmonit.com/monit/) service which can be used to monitor
processes, services or even other hosts. You can also use this role as
a dependency of another role and configure monitoring service for an
application this way.

Alerts can be sent to an e-mail address (by default
`monitoring@<your-domain>`, or to a mobile phone or pager using an SMS
gateway (for example one managed by `debops.smstools` role).

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.monit

### Documentation

More information about `debops.monit` can be found in the
[official debops.monit documentation](http://docs.debops.org/en/latest/ansible/roles/debops.monit.html).


### Role dependencies

- `debops.etc_services`
- `debops.apt_preferences`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`monit` role was written by:
- Nick Janetakis | [e-mail](mailto:nick.janetakis@gmail.com) | [Twitter](https://twitter.com/nickjanetakis) | [GitHub](https://github.com/nickjj)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
