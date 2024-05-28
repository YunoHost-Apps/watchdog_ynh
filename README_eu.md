<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Watchdog YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/watchdog.svg)](https://dash.yunohost.org/appci/app/watchdog) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/watchdog.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/watchdog.maintain.svg)

[![Instalatu Watchdog YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchdog)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Watchdog YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

A watchdog service makes sure your server is still running and reboots it if necessary.  
It better (only?) works if your server has a [hardware watchdog device](https://en.wikipedia.org/wiki/Watchdog_timer).

The included sercice will regularly write to `/dev/watchdog`. If it stops, then the freeze is detected and server rebooted.

This app has only been tested on Raspberry Pi.


**Paketatutako bertsioa:** 5.16~ynh2
## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://sourceforge.net/projects/watchdog/>
- YunoHost Denda: <https://apps.yunohost.org/app/watchdog>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/watchdog_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
edo
sudo yunohost app upgrade watchdog -u https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
