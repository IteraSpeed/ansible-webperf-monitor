thomass.common
==============

Executes common tasks useful for most other ansible roles:

* Updates the apt cache if outdated.
* Enables ansible configuring mysql.
* Enables ansible the use of the rsync module via sudo.

Variables
---------

Alse see [defaults](defaults/main.yml)

| Variable             | Default        | Description                                                                  |
|----------------------|----------------|------------------------------------------------------------------------------|
| apt_cache_valid_time | 86400 (1 day)  | The time in seconds when the apt cache becomes outdated and will be updated. |

Licence
-------

The whole repository is licenced under BSD. Please mention following:

gitlab.xarif.de / ThomasSteinbach (thomass at aikq.de)