<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Zola pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/zola.svg)](https://dash.yunohost.org/appci/app/zola) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/zola.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/zola.maintain.svg)

[![Installer Zola avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zola)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Zola rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Zola est un [générateur de site statique](https://fr.wikipedia.org/wiki/G%C3%A9n%C3%A9rateur_de_site_statique).

Avec ce package, Zola régénérera automatiquement ([à l'aide de Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) votre site web si une modification est apportée à vos sources.


**Version incluse :** 0.18.0~ynh2

## Captures d’écran

![Capture d’écran de Zola](./doc/screenshots/zola-screenshot.jpg)

## Documentations et ressources

- Site officiel de l’app : <https://www.getzola.org/>
- Documentation officielle de l’admin : <https://www.getzola.org/documentation/getting-started/overview/>
- Dépôt de code officiel de l’app : <https://github.com/getzola/zola>
- YunoHost Store : <https://apps.yunohost.org/app/zola>
- Signaler un bug : <https://github.com/YunoHost-Apps/zola_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/zola_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
ou
sudo yunohost app upgrade zola -u https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
