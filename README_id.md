<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# ESPHome untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/esphome)](https://ci-apps.yunohost.org/ci/apps/esphome/)
![Status kerja](https://apps.yunohost.org/badge/state/esphome)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/esphome)

[![Pasang ESPHome dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=esphome)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang ESPHome secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

ESPHome is a system to control your microcontrollers by simple yet powerful configuration files and control them remotely through Home Automation systems. All you need to do is write YAML configuration files; the rest (over-the-air updates, compiling) is all handled by ESPHome.


**Versi terkirim:** 2025.3.1~ynh1

**Demo:** <https://web.esphome.io/>

## Tangkapan Layar

![Tangkapan Layar pada ESPHome](./doc/screenshots/hero.png)
![Tangkapan Layar pada ESPHome](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://esphome.io/>
- Dokumentasi pengguna resmi: <https://esphome.io>
- Depot kode aplikasi hulu: <https://github.com/esphome/esphome>
- Gudang YunoHost: <https://apps.yunohost.org/app/esphome>
- Laporkan bug: <https://github.com/YunoHost-Apps/esphome_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/esphome_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/esphome_ynh/tree/testing --debug
atau
sudo yunohost app upgrade esphome -u https://github.com/YunoHost-Apps/esphome_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
