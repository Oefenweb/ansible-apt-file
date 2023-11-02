## apt-file

[![CI](https://github.com/Oefenweb/ansible-apt-file/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-apt-file/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-apt--file-blue.svg)](https://galaxy.ansible.com/Oefenweb/apt_file)

Set up apt-file in Debian-like systems.

#### Requirements

None

#### Variables

* `apt_file_quiet`: [default: `true`]: Whether or not the jobs should run quietly
* `apt_file_quietness`: [default: `'&>'`]: Controls the "quietness" of the jobs (e.g. `'>'` for only `stderr`)

* `apt_file_update_daily` [default: `true`]: Whether or not to update on daily basis

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.apt-file
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-apt-file/issues)!
