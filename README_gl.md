<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Watchdog para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/watchdog.svg)](https://dash.yunohost.org/appci/app/watchdog) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/watchdog.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/watchdog.maintain.svg)

[![Instalar Watchdog con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchdog)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Watchdog de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

A watchdog service makes sure your server is still running and reboots it if necessary.
It better (only?) works if your server has a hardware watchdog device.

The included sercice will regularly write to `/dev/watchdog`. If it stops, then the freeze is detected and server rebooted.

This app has only been tested on Raspberry Pi.


**Versión proporcionada:** 5.16~ynh1
## Documentación e recursos

- Repositorio de orixe do código: <https://sourceforge.net/projects/watchdog/>
- Tenda YunoHost: <https://apps.yunohost.org/app/watchdog>
- Informar dun problema: <https://github.com/YunoHost-Apps/watchdog_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
ou
sudo yunohost app upgrade watchdog -u https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
