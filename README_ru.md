<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# ESPHome для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/esphome)](https://ci-apps.yunohost.org/ci/apps/esphome/)
![Состояние работы](https://apps.yunohost.org/badge/state/esphome)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/esphome)

[![Установите ESPHome с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=esphome)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить ESPHome быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

ESPHome is a system to control your microcontrollers by simple yet powerful configuration files and control them remotely through Home Automation systems. All you need to do is write YAML configuration files; the rest (over-the-air updates, compiling) is all handled by ESPHome.


**Поставляемая версия:** 2025.2.0~ynh1

**Демо-версия:** <https://web.esphome.io/>

## Снимки экрана

![Снимок экрана ESPHome](./doc/screenshots/hero.png)
![Снимок экрана ESPHome](./doc/screenshots/screenshot.png)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://esphome.io/>
- Официальная документация пользователя: <https://esphome.io>
- Репозиторий кода главной ветки приложения: <https://github.com/esphome/esphome>
- Магазин YunoHost: <https://apps.yunohost.org/app/esphome>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/esphome_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/esphome_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/esphome_ynh/tree/testing --debug
или
sudo yunohost app upgrade esphome -u https://github.com/YunoHost-Apps/esphome_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
