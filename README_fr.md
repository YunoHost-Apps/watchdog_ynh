<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Watchdog pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/watchdog.svg)](https://ci-apps.yunohost.org/ci/apps/watchdog/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/watchdog.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/watchdog.maintain.svg)

[![Installer Watchdog avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=watchdog)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Watchdog rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Un service de surveillance *watchdog* s'assure que votre serveur tourne toujours, et le redémarre si nécessaire.  
Il tournera préférentiellement (uniquement?) si votre serveur est équipé d'un [*watchdog*](https://fr.wikipedia.org/wiki/Chien_de_garde_(informatique)) matériel.

Le service inclut ira régulièrement écrire dans `/dev/watchdog`. S'il s'arrête, le plantage est alors détecté et résolu par un redémarrage du système.

Cette application n'a été testée que sur Raspberry Pi.


**Version incluse :** 5.16~ynh3
## Documentations et ressources

- Dépôt de code officiel de l’app : <https://sourceforge.net/projects/watchdog/>
- YunoHost Store : <https://apps.yunohost.org/app/watchdog>
- Signaler un bug : <https://github.com/YunoHost-Apps/watchdog_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
ou
sudo yunohost app upgrade watchdog -u https://github.com/YunoHost-Apps/watchdog_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
