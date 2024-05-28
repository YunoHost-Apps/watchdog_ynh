<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Watchdog per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/watchdog.svg)](https://dash.yunohost.org/appci/app/watchdog) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/watchdog.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/watchdog.maintain.svg)

[![Installa Watchdog con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchdog)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Watchdog su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

A watchdog service makes sure your server is still running and reboots it if necessary.
It better (only?) works if your server has a hardware watchdog device.

The included sercice will regularly write to `/dev/watchdog`. If it stops, then the freeze is detected and server rebooted.

This app has only been tested on Raspberry Pi.


**Versione pubblicata:** 5.16~ynh1
## Documentazione e risorse

- Repository upstream del codice dell’app: <https://sourceforge.net/projects/watchdog/>
- Store di YunoHost: <https://apps.yunohost.org/app/watchdog>
- Segnala un problema: <https://github.com/YunoHost-Apps/watchdog_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
o
sudo yunohost app upgrade watchdog -u https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
