<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Watchdog para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/watchdog.svg)](https://dash.yunohost.org/appci/app/watchdog) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/watchdog.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/watchdog.maintain.svg)

[![Instalar Watchdog con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchdog)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarWatchdog rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

A watchdog service makes sure your server is still running and reboots it if necessary.  
It better (only?) works if your server has a [hardware watchdog device](https://en.wikipedia.org/wiki/Watchdog_timer).

The included sercice will regularly write to `/dev/watchdog`. If it stops, then the freeze is detected and server rebooted.

This app has only been tested on Raspberry Pi.


**Versión actual:** 5.16~ynh2
## Documentaciones y recursos

- Repositorio del código fuente oficial de la aplicación : <https://sourceforge.net/projects/watchdog/>
- Catálogo YunoHost: <https://apps.yunohost.org/app/watchdog>
- Reportar un error: <https://github.com/YunoHost-Apps/watchdog_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
o
sudo yunohost app upgrade watchdog -u https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
