frontend
========
- Installs latest `nodejs` and `npm` from official repos
- Installs `ember-cli`
- Installs `sass`

Role Variables
--------------
| Variable | Description | Default value |
|----------|-------------|---------------|
|`frontend_packages`| List of system-level packages to install | `[nodejs]` |
|`frontend_repo_key_url`| URL of the repo key | `https://deb.nodesource.com/gpgkey/nodesource.gpg.key` |
|`frontend_repos`| List of repos that provide `nodejs` and `npm` | See below |

Default values for `frontend_repos`:
- 'deb https://deb.nodesource.com/node_5.x trusty main'
- 'deb-src https://deb.nodesource.com/node_5.x trusty main'

Dependencies
------------
none

License
-------
BSD
