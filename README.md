shadowsocks
===========

[![PyPI version]][PyPI]

A fast tunnel proxy that helps you bypass firewalls.

Server
------

### Install

Debian / Ubuntu:

    apt-get install python-pip
    pip install shadowsocks

CentOS:

    yum install python-setuptools && easy_install pip
    pip install shadowsocks

Windows:

See [Install Server on Windows]

### Usage

    ssserver -p 443 -k password -m aes-256-cfb

To run in the background:

    sudo ssserver -p 443 -k password -m aes-256-cfb --user nobody -d start

To stop:

    sudo ssserver -d stop

To check the log:

    sudo less /var/log/shadowsocks.log

Check all the options via `-h`. You can also use a [Configuration] file
instead.

Client
------

* [Windows] / [OS X]
* [Android] / [iOS]
* [OpenWRT]

Use GUI clients on your local PC/phones. Check the README of your client
for more information.

Documentation
-------------

You can find all the documentation in the [Wiki].

License
-------

Copyright 2015 clowwindy

Licensed under the Apache License, Version 2.0 (the "License"); you may
not use this file except in compliance with the License. You may obtain
a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations
under the License.

Bugs and Issues
----------------

* [Troubleshooting]
* [Issue Tracker]



[Android]:           https://github.com/shadowsocks/shadowsocks-android
[Configuration]:     https://github.com/breakwa11/shadowsocks-rss/wiki/Server-Setup
[Debian sid]:        https://packages.debian.org/unstable/python/shadowsocks
[iOS]:               https://github.com/shadowsocks/Potatso
[Issue Tracker]:     https://github.com/breakwa11/shadowsocks/issues?state=open
[Install Server on Windows]: https://github.com/shadowsocks/shadowsocks/wiki/Install-Shadowsocks-Server-on-Windows
[OpenWRT]:           https://github.com/shadowsocks/openwrt-shadowsocks
[OS X]:              https://github.com/shadowsocks/shadowsocks-iOS/wiki/Shadowsocks-for-OSX-Help
[PyPI]:              https://pypi.python.org/pypi/shadowsocks
[PyPI version]:      https://img.shields.io/pypi/v/shadowsocks.svg?style=flat
[Troubleshooting]:   https://github.com/shadowsocks/shadowsocks/wiki/Troubleshooting
[Wiki]:              https://github.com/breakwa11/shadowsocks-rss/wiki
[Windows]:           https://github.com/breakwa11/shadowsocks-csharp
