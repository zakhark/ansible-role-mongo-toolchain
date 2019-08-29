Ansible role for mongo-toolchain
==================================

Installs the mongo toolchain

[![CircleCI](https://img.shields.io/circleci/build/github/mongodb-ansible-roles/ansible-role-mongo-toolchain/master?style=flat-square)](https://circleci.com/gh/mongodb-ansible-roles/ansible-role-mongo-toolchain)

Requirements
------------

Issue when testing on Docker for Mac: [docker/hub-feedback#727], you must download this version of Docker: [Docker 18.06.0-ce](https://github.com/docker/docker-ce/releases/tag/v18.06.0-ce) and then set the Docker daemon `storage-driver` to `aufs`.
```javascript
{
  "storage-driver" : "aufs"
}
```
You can change this setting via `Preferences` -> `Daemon` -> `Advanced`

Role Variables
--------------

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-------:|:--------:|
| mongo\_toolchain\_sha | SHA of the golang toolchain you want to download | string | "" | yes |
| mongo\_toolchain\_dest | Destination to download toolchain | string | "/opt" | no |

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: ansible-role-mongo-toolchain
      vars:
        mongo_toolchain_sha: 1440f2ce9521f9756565ce4a9a45ee382414a80e
```

Development
-----------

Testing this role locally requires the CircleCI [Local CLI](https://circleci.com/docs/2.0/local-cli/).

To install the CLI for macOS and Linux, invoke the following command:

    $ curl -fLSs https://circle.ci/cli | DESTDIR=/usr/local/bin bash

After installing the CLI, invoke the following command to run the Molecule tests:

    $ make test

License
-------

[Apache License](LICENSE)
