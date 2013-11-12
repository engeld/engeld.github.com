---
layout: post
title: "Firefox Sync Server on Uberspace"

---

Since I only use Firefox it only seems logical that I use their sync-service.
However, I don't want to use Mozilla's server, so I have to configure and operate my own.

This serves as my personal brain dump of the process to install Firefox Sync on my Uberspace.

Prerequisites
-------------

Make sure the system has [`python 2.6`][01] and [`virtualenv`][02] installed. On newer Uberspace's Python 2.6 is a
no-brainer but on my old system the default python-version is 2.4. To install Virtualenv I install [`pip`][03]

```bash
$ mkdir -p ~/lib/python2.6/site/packages
$ export PYTHONPATH=~/lib/python2.6/site-packages   # put this in .bash_profile afterwards
$ easy_install-2.6 --prefix=~ pip
$ pip install -t ~/lib/python2.6/site-packages virtualenv
```



[01]:   http://python.org/download/releases/2.6.6
[02]:   http://pypi.python.org/pypi/virtualenv
[03]:   http://www.pip-installer.org/en/latest/
