![Build Status](https://api.travis-ci.org/dockpack/base_git.svg)

**base_git** is an ansible-role to install the Git version control client.
This role allows the use of git 2.18 on RHEL 6 instead of the legacy.

Requirements
------------

RHEL-like, or Debian/Ubuntu system
Yum infrastructure, or internet.

Role Variables
--------------

- Software collections offer concurrent versions of programming tools
```
    collections_enabled: true
```

- preferred collection when collections are enabled
```
    base_git: rh-git218
```

- Change these defaults for optional packages.
```
    base_git_rpms
```

Dependencies
------------

https://www.softwarecollections.org/en/docs/


Example Usage
----------------

Refer to a complete build server https://github.com/bbaassssiiee/buildserver

License
-------

MIT

Author Information
------------------

Bas Meijer
@bbaassssiiee
