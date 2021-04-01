# ChuWiki pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/chuwiki.svg)](https://dash.yunohost.org/appci/app/chuwiki) ![](https://ci-apps.yunohost.org/ci/badges/chuwiki.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/chuwiki.maintain.svg)  
[![Installer chuwiki avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chuwiki)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer ChuWiki rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Un wiki simple, rapide et flexible.

**Version incluse :** 2.0

## Configuration

Comment configurer cette application : via le fichier `configuration.ini`.

## Documentation

 * Documentation officielle : http://chuwiki.genezys.net/
 * Documentation YunoHost : Si une documentation spécifique est nécessaire, n'hésitez pas à contribuer.

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP et HTTP est-elle prise en charge ? Oui.
* L'application peut-elle être utilisée par plusieurs utilisateurs ? Oui, mais cela n'est pas spécifique a YunoHost mais a l'app.

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/chuwiki%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/chuwiki/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/chuwiki%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/chuwiki/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/chuwiki_ynh/issues
 * Site de l'application : http://chuwiki.genezys.net/
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing --debug
ou
sudo yunohost app upgrade chuwiki -u https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing --debug
```
