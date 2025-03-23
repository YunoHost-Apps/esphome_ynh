<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# ESPHome pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/esphome)](https://ci-apps.yunohost.org/ci/apps/esphome/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/esphome)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/esphome)

[![Installer ESPHome avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=esphome)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer ESPHome rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

ESPHome est un système permettant de contrôler vos microcontrôleurs par des fichiers de configuration simples mais puissants et de les contrôler à distance par le biais de systèmes domotiques. Tout ce que vous avez à faire est d'écrire des fichiers de configuration YAML ; le reste (mises à jour over-the-air, compilation) est entièrement pris en charge par ESPHome.


**Version incluse :** 2025.3.0~ynh1

**Démo :** <https://web.esphome.io/>

## Captures d’écran

![Capture d’écran de ESPHome](./doc/screenshots/hero.png)
![Capture d’écran de ESPHome](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://esphome.io/>
- Documentation officielle utilisateur : <https://esphome.io>
- Dépôt de code officiel de l’app : <https://github.com/esphome/esphome>
- YunoHost Store : <https://apps.yunohost.org/app/esphome>
- Signaler un bug : <https://github.com/YunoHost-Apps/esphome_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/esphome_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/esphome_ynh/tree/testing --debug
ou
sudo yunohost app upgrade esphome -u https://github.com/YunoHost-Apps/esphome_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
