# Pre-compiled gucamole server packages
The repository contains instructions how to compile the gucamole server `guacd` to be used by the rport server.

It also contains ready-to-use packages for Debian 11 (bullseye).

## Install on Debian
To install the guacamole server proceed as follows.
```bash
apt install libcairo2 libjpeg62-turbo libpng16-16 libwebp6 libfontconfig1 libfreetype6
curl -LO https://bitbucket.org/cloudradar/rport-guacamole/downloads/
dpkg -i rport-guacamole_1.4.0_debian_bullseye_amd64.deb
```

To avoid conflics with a potentially already running instance of `guacd` it's installed to `/opt/rport-guacamole`.

## Compile and package
If you preferr to compile and package your self, just execute the scripts of the repository on your machine.

## License
The [Apache Guacamole™ source code](https://guacamole.apache.org/) is released under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).

## Liability disclaimer
Use the instructions or the pre-compiled packages on your own risk.
This repository is not part of the Apache Guacamole™ project. 