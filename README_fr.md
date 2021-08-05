# Vikunja pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/miniflux.svg)](https://dash.yunohost.org/appci/app/miniflux) ![](https://ci-apps.yunohost.org/ci/badges/miniflux.status.svg)  ![](https://ci-apps.yunohost.org/ci/badges/miniflux.maintain.svg)
[![Installer miniflux avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=miniflux)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install miniflux quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Vue d'ensemble

Agrégateur de flux RSS minimaliste

**Version incluse:** 2.0.30~ynh1




## Captures d'écran


   ![](./doc/screenshots/overview.png)




## Avertissements / informations importantes

## Configuration

Vous pouvez configurer Miniflux en modifiant le fichier `/var/www/miniflux/miniflux.conf` en vous aidant de la [documentation](https://miniflux.app/docs/configuration.html).


## Documentations et ressources

* Site official de l'app : https://miniflux.app/

* Documentation officielle de l'admin: https://miniflux.app/docs/index.html
* Dépôt de code officiel de l'app:  https://github.com/miniflux/v2
* Documentation YunoHost pour cette app: https://yunohost.org/app_miniflux
* Signaler un bug: https://github.com/YunoHost-Apps/miniflux_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/miniflux_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/miniflux_ynh/tree/testing --debug
or
sudo yunohost app upgrade miniflux -u https://github.com/YunoHost-Apps/miniflux_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications:** https://yunohost.org/packaging_apps