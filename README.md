# sw_vers in shell
An attempt of writing macOS's sw_vers in POSIX shell script

(this isn't meant to be used seriously)

You can find an example of SystemVersion.plist
[here](https://raw.githubusercontent.com/alemontn/sw_vers/main/SystemVersion.plist)

By default, the file is placed in /etc/SystemVersion.plist
but the location can be changed in the script

## Installation
```shell
$ curl -Ls -o /tmp/sw_vers https://raw.githubusercontent.com/alemontn/sw_vers/main/sw_vers
# install -m755 /tmp/sw_vers /usr/bin/sw_vers
$ sw_vers
```

### License
This script is licensed under the
[FreeBSD or "BSD 2-clause"](https://en.wikipedia.org/wiki/FreeBSD_Documentation_License)
license.
