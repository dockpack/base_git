![Build Status](https://api.travis-ci.org/dockpack/base_git.svg)

**base_git** is an ansible-role to install the Git version control client using Satellite, Yum or APT.
This role allows the use of git 2.9.3 on RHEL 6 instead of the legacy 1.7.1 by means of subscribimng to the Software Collections. This is great for on-premise solutions.

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
