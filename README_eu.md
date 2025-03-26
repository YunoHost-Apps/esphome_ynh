<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# ESPHome YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/esphome)](https://ci-apps.yunohost.org/ci/apps/esphome/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/esphome)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/esphome)

[![Instalatu ESPHome YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=esphome)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek ESPHome YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

ESPHome is a system to control your microcontrollers by simple yet powerful configuration files and control them remotely through Home Automation systems. All you need to do is write YAML configuration files; the rest (over-the-air updates, compiling) is all handled by ESPHome.


**Paketatutako bertsioa:** 2025.3.2~ynh1

**Demoa:** <https://web.esphome.io/>

## Pantaila-argazkiak

![ESPHome(r)en pantaila-argazkia](./doc/screenshots/hero.png)
![ESPHome(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://esphome.io/>
- Erabiltzaileen dokumentazio ofiziala: <https://esphome.io>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/esphome/esphome>
- YunoHost Denda: <https://apps.yunohost.org/app/esphome>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/esphome_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/esphome_ynh/tree/testing).

`testing` abarra probatzeko, honakoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/esphome_ynh/tree/testing --debug
edo
sudo yunohost app upgrade esphome -u https://github.com/YunoHost-Apps/esphome_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
