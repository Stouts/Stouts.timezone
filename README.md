Stouts.timezone
===============

[![Build Status](http://img.shields.io/travis/Stouts/Stouts.timezone.svg?style=flat-square)](https://travis-ci.org/Stouts/Stouts.timezone)
[![Galaxy](http://img.shields.io/badge/galaxy-Stouts.timezone-blue.svg?style=flat-square)](https://galaxy.timezone.com/list#/roles/909)
[![Tag](http://img.shields.io/github/tag/Stouts/Stouts.timezone.svg?style=flat-square)]()

Ansible role which manage timezone (debian)

#### Variables
```yaml
timezone_enabled: yes                   # The role is enabled
timezone_timezone: UTC                  # Set timezone
```

#### Usage

Add `Stouts.timezone` to your roles and set vars in your playbook file.

Example:

```yaml

- hosts: all

  roles:
    - Stouts.timezone

  vars:
    timezone_timezone: Europe/Moscow

```

#### License

Licensed under the MIT License. See the LICENSE file for details.

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Stouts/Stouts.timezone/issues)!

