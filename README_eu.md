<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# ChuWiki YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/chuwiki.svg)](https://dash.yunohost.org/appci/app/chuwiki) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/chuwiki.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/chuwiki.maintain.svg)

[![Instalatu ChuWiki YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chuwiki)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek ChuWiki YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

ChuWiki is first and foremost a wiki. A wiki is a website whose pages can be edited by the visitor. However, a history system allows you to track modifications made to a page and restore an old version of the page if necessary.

**Paketatutako bertsioa:** 2.0~ynh3

**Demoa:** <http://chuwiki.genezys.net/wiki/Bac%20%C3%A0%20sable>

## Pantaila-argazkiak

![ChuWiki(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Jatorrizko garapena utzita**: Software honek ez du arduradunik. Denborak aurrera egin ahala funtzionatzeari utziko dio, konpondu gabeko segurtasun arazoak izango ditu, etab.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <http://chuwiki.genezys.net/>
- Administratzaileen dokumentazio ofiziala: <http://chuwiki.genezys.net/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/genezys/chuwiki>
- YunoHost Denda: <https://apps.yunohost.org/app/chuwiki>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/chuwiki_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing --debug
edo
sudo yunohost app upgrade chuwiki -u https://github.com/YunoHost-Apps/chuwiki_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
