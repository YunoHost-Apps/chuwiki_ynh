# ChuWiki for YunoHost

[![Integration level](https://dash.yunohost.org/integration/chuwiki.svg)](https://dash.yunohost.org/appci/app/chuwiki) ![](https://ci-apps.yunohost.org/ci/badges/chuwiki.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/chuwiki.maintain.svg)  
[![Install chuwiki with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chuwiki)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install ChuWiki quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
A simple, fast and flexible wiki.

**Shipped version:** 2.0

## Configuration

How to configure this app: From `configuration.ini` file.

## Documentation

 * Official documentation: http://chuwiki.genezys.net/
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

Are LDAP and HTTP auth supported? Yes.
Can the app be used by multiple users? Yes, but it is not specific to YunoHost but to the app.

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/chuwiki%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/chuwiki/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/chuwiki%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/chuwiki/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/chuwiki_ynh/issues
 * App website: http://chuwiki.genezys.net/
 * YunoHost website: https://yunohost.org/

---

## Developer info

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing --debug
or
sudo yunohost app upgrade chuwiki -u https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing --debug
```
