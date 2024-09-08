<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Watchdog для YunoHost

[![Уровень интеграции](https://dash.yunohost.org/integration/watchdog.svg)](https://ci-apps.yunohost.org/ci/apps/watchdog/) ![Состояние работы](https://ci-apps.yunohost.org/ci/badges/watchdog.status.svg) ![Состояние сопровождения](https://ci-apps.yunohost.org/ci/badges/watchdog.maintain.svg)

[![Установите Watchdog с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchdog)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Watchdog быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

A watchdog service makes sure your server is still running and reboots it if necessary.  
It better (only?) works if your server has a [hardware watchdog device](https://en.wikipedia.org/wiki/Watchdog_timer).

The included sercice will regularly write to `/dev/watchdog`. If it stops, then the freeze is detected and server rebooted.

This app has only been tested on Raspberry Pi.


**Поставляемая версия:** 5.16~ynh4
## Документация и ресурсы

- Репозиторий кода главной ветки приложения: <https://sourceforge.net/projects/watchdog/>
- Магазин YunoHost: <https://apps.yunohost.org/app/watchdog>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/watchdog_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
или
sudo yunohost app upgrade watchdog -u https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
