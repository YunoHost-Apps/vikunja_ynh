<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Vikunja YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/vikunja)](https://ci-apps.yunohost.org/ci/apps/vikunja/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/vikunja)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/vikunja)

[![Instalatu Vikunja YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=vikunja)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Vikunja YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Vikunja is a self-hosted open-source to-do list application for all platforms.

### Features

- Stay organized 
- Collaborate with peers
- Tasks  
- Kanban board
- CalDAV
- Links  

**Paketatutako bertsioa:** 0.24.6~ynh1

**Demoa:** <https://try.vikunja.io/login>

## Pantaila-argazkiak

![Vikunja(r)en pantaila-argazkia](./doc/screenshots/kanban.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://vikunja.io/>
- Administratzaileen dokumentazio ofiziala: <https://vikunja.io/docs/>
- Jatorrizko aplikazioaren kode-gordailua: <https://kolaente.dev/vikunja/vikunja>
- YunoHost Denda: <https://apps.yunohost.org/app/vikunja>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/vikunja_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing --debug
edo
sudo yunohost app upgrade vikunja -u https://github.com/YunoHost-Apps/vikunja_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
