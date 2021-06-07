# ChuWiki pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/chuwiki.svg)](https://dash.yunohost.org/appci/app/chuwiki) ![](https://ci-apps.yunohost.org/ci/badges/chuwiki.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/chuwiki.maintain.svg)  
[![Installer ChuWiki avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chuwiki)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer ChuWiki rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Un wiki simple, rapide et flexible.

**Version incluse :** 2.0~ynh1

**Démo :** http://chuwiki.genezys.net/wiki/Bac%20%C3%A0%20sable

## Avertissements / informations importantes

## Configuration

Comment configurer cette application : via le fichier `/var/www/chuwiki/configuration.ini`.

## Documentations et ressources

* Site officiel de l'app : http://chuwiki.genezys.net/
* Documentation officielle utilisateur : https://yunohost.org/apps
* Documentation officielle de l'admin : http://chuwiki.genezys.net/
* Dépôt de code officiel de l'app : https://github.com/genezys/chuwiki
* Documentation YunoHost pour cette app : https://yunohost.org/app_chuwiki
* Signaler un bug : https://github.com/YunoHost-Apps/chuwiki_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing --debug
ou
sudo yunohost app upgrade chuwiki -u https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps