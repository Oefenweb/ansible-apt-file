## apt-file

[![Build Status](https://travis-ci.org/Oefenweb/ansible-apt-file.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-apt-file) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-apt--file-blue.svg)](https://galaxy.ansible.com/tersmitten/apt-file)

Set up apt-file in Debian-like systems.

#### Requirements

None

#### Variables

* `apt_file_update_daily` [default: `true`]: Whether or not to update on daily basis

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - apt-file
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-apt-file/issues)!
