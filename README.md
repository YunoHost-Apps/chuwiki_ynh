<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# ChuWiki for YunoHost

[![Integration level](https://dash.yunohost.org/integration/chuwiki.svg)](https://dash.yunohost.org/appci/app/chuwiki) ![Working status](https://ci-apps.yunohost.org/ci/badges/chuwiki.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/chuwiki.maintain.svg)

[![Install ChuWiki with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chuwiki)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install ChuWiki quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

ChuWiki is first and foremost a wiki. A wiki is a website whose pages can be edited by the visitor. However, a history system allows you to track modifications made to a page and restore an old version of the page if necessary.

**Shipped version:** 2.0~ynh2

**Demo:** http://chuwiki.genezys.net/wiki/Bac%20%C3%A0%20sable

## Screenshots

![Screenshot of ChuWiki](./doc/screenshots/screenshot.png)

## :red_circle: Antifeatures

- **Upstream not maintained**: This software is not maintained anymore. Expect it to break down over time, be exposed to unfixed security breaches, etc.

## Documentation and resources

* Official app website: <http://chuwiki.genezys.net/>
* Official admin documentation: <http://chuwiki.genezys.net/>
* Upstream app code repository: <https://github.com/genezys/chuwiki>
* YunoHost Store: <https://apps.yunohost.org/app/chuwiki>
* Report a bug: <https://github.com/YunoHost-Apps/chuwiki_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing --debug
or
sudo yunohost app upgrade chuwiki -u https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
