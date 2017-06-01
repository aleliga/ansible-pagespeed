## [![Nabla](https://debops.org/images/debops-small.png)](https://github.com/AlbanAndrieu) alban_andrieu_pagespeed

<!-- This file was generated by Ansigenome. Do not edit this file directly but
     instead have a look at the files in the ./meta/ directory. -->

[![License](http://img.shields.io/:license-apache-blue.svg?style=flat-square)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Travis CI](https://img.shields.io/travis/AlbanAndrieu/ansible-pagespeed.svg?style=flat)](https://travis-ci.org/AlbanAndrieu/ansible-pagespeed)
[![Branch](http://img.shields.io/github/tag/AlbanAndrieu/ansible-pagespeed.svg?style=flat-square)](https://github.com/AlbanAndrieu/ansible-pagespeed/tree/master)
[![Donate](https://img.shields.io/gratipay/AlbanAndrieu.svg?style=flat)](https://www.gratipay.com/~AlbanAndrieu)
<!--[![Ansible Galaxy](https://img.shields.io/badge/galaxy-alban.andrieu.pagespeed-660198.svg?style=flat)](https://galaxy.ansible.com/detail#/role/1992)-->
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-alban.andrieu.pagespeed-660198.svg?style=flat)](https://galaxy.ansible.com/alban.andrieu/pagespeed)
[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)
[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=AlbanAndrieu&url=https://github.com/AlbanAndrieu/ansible-pagespeed&title=ansible-pagespeed&language=en_GB&tags=github&category=software)

Ensures that mod pagespeed is installed (using apt) on apache


### Role dependencies

- `geerlingguy.apache`
### Installation

This role requires at least Ansible `v2.3.0.0`. To install it, run:

Using `ansible-galaxy`:
```shell
$ ansible-galaxy install alban.andrieu.pagespeed
```

Using `arm` ([Ansible Role Manager](https://github.com/mirskytech/ansible-role-manager/)):
```shell
$ arm install alban.andrieu.pagespeed
```

Using `git`:
```shell
$ git clone https://github.com/AlbanAndrieu/ansible-pagespeed.git
```

### Documentation

<!---
More information about `alban.andrieu.pagespeed` can be found in the
[official alban.andrieu.pagespeed documentation](https://docs.debops.org/en/latest/ansible/roles/ansible-pagespeed/docs/).
-->


### Role variables

List of default variables available in the inventory:

```YAML
pagespeed_enabled: yes                       # Enable module

pagespeed_dir_tmp: "/tmp" # or override with "{{ tempdir.stdout }} in order to have be sure to download the file"

pagespeed_package_arch: "amd64"
pagespeed_package_deb: "mod-pagespeed-stable_current_{{ pagespeed_package_arch }}.deb"
pagespeed_url: "https://dl-ssl.google.com/dl/linux/direct/{{ pagespeed_package_deb }}"
```


### Detailed usage guide

Describe how to use in more detail...


### Authors and license

`alban_andrieu_pagespeed` role was written by:

- [Alban Andrieu](fr.linkedin.com/in/nabla/) | [e-mail](mailto:alban.andrieu@free.fr) | [Twitter](https://twitter.com/AlbanAndrieu) | [GitHub](https://github.com/AlbanAndrieu)

- License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

Copyright (c) 2017 [Alban Andrieu](https://alban.andrieu.com/)

### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/AlbanAndrieu/ansible-pagespeed/issues)!

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests and examples for any new or changed functionality.

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

***

This role is part of the [Nabla](https://github.com/AlbanAndrieu) project.
README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).
