Install and configure my dashboard
=========

The role installs and configures my [simple dashboard](https://github.com/tychobrouwer/simple-dashboard-go).

Role Variables
--------------

A list of the variables that need to be set can be seen below

Example Playbook
----------------

```yaml
- hosts: servers
  vars:
    dashboard_config_template: templates/dashboard-config.yaml.j2

  roles:
      - role: tychobrouwer.dashboard
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
