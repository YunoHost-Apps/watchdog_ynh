<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Watchdog untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/watchdog.svg)](https://ci-apps.yunohost.org/ci/apps/watchdog/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/watchdog.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/watchdog.maintain.svg)

[![Pasang Watchdog dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchdog)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Watchdog secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

A watchdog service makes sure your server is still running and reboots it if necessary.  
It better (only?) works if your server has a [hardware watchdog device](https://en.wikipedia.org/wiki/Watchdog_timer).

The included sercice will regularly write to `/dev/watchdog`. If it stops, then the freeze is detected and server rebooted.

This app has only been tested on Raspberry Pi.


**Versi terkirim:** 5.16~ynh4
## Dokumentasi dan sumber daya

- Depot kode aplikasi hulu: <https://sourceforge.net/projects/watchdog/>
- Gudang YunoHost: <https://apps.yunohost.org/app/watchdog>
- Laporkan bug: <https://github.com/YunoHost-Apps/watchdog_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
atau
sudo yunohost app upgrade watchdog -u https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
