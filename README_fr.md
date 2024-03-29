<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Vikunja pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/vikunja.svg)](https://dash.yunohost.org/appci/app/vikunja) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/vikunja.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/vikunja.maintain.svg)

[![Installer Vikunja avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=vikunja)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Vikunja rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Vikunja est une application de liste de tâches Open Source auto-hébergée pour toutes les plateformes.

### Features

- Stay organized 
- Collaborate with peers
- Tasks  
- Kanban board
- CalDAV
- Links  

**Version incluse :** 0.22.1~ynh1

**Démo :** <https://try.vikunja.io/login>

## Captures d’écran

![Capture d’écran de Vikunja](./doc/screenshots/kanban.png)

## Documentations et ressources

- Site officiel de l’app : <https://vikunja.io/>
- Documentation officielle de l’admin : <https://vikunja.io/docs/>
- Dépôt de code officiel de l’app : <https://kolaente.dev/vikunja/vikunja>
- YunoHost Store : <https://apps.yunohost.org/app/vikunja>
- Signaler un bug : <https://github.com/YunoHost-Apps/vikunja_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing --debug
ou
sudo yunohost app upgrade vikunja -u https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
