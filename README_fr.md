# Vikunja pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/vikunja.svg)](https://dash.yunohost.org/appci/app/vikunja) ![](https://ci-apps.yunohost.org/ci/badges/vikunja.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/vikunja.maintain.svg)  
[![Installer Vikunja avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=vikunja)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Vikunja rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Vikunja est une application de liste de tâches Open Source auto-hébergée pour toutes les plateformes.

**Version incluse :** 0.18.1~ynh2

**Démo :** https://try.vikunja.io/login

## Captures d'écran

![](./doc/screenshots/kanban.png)

## Avertissements / informations importantes

## Configuration

Vous pouvez configurer Vikunja en modifiant le fichier `/opt/vikunja/config.yml` en vous aidant de la [documentation](https://vikunja.io/docs/config-options/).
## Documentations et ressources

* Site officiel de l'app : https://vikunja.io/
* Documentation officielle de l'admin : https://vikunja.io/docs/
* Dépôt de code officiel de l'app : https://kolaente.dev/vikunja/
* Documentation YunoHost pour cette app : https://yunohost.org/app_vikunja
* Signaler un bug : https://github.com/YunoHost-Apps/vikunja_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing --debug
ou
sudo yunohost app upgrade vikunja -u https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps