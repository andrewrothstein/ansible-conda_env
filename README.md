andrewrothstein.conda_env
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-conda_env.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-conda_env)

Creates a named [Conda](http://conda.pydata.org/docs/index.html) environment.

Requirements
------------

Assumes you have installed either Anaconda or Miniconda. Please consider these roles [andrewrothstein.anaconda](https://github.com/andrewrothstein/ansible-anaconda) and [andrewrothstein.miniconda](https://github.com/andrewrothstein/ansible-miniconda) for your needs.

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - role: andrewrothstein.conda_env
      conda_env_name: my-environment
      conda_env_environment: my-environment.yml
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
