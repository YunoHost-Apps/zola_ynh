<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Zola voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/zola)](https://ci-apps.yunohost.org/ci/apps/zola/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/zola)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/zola)

[![Zola met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zola)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Zola snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Zola is a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator).

With this package, Zola will automatically regenerate ([using Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) your website if any change is made to your sources.


**Geleverde versie:** 0.20.0~ynh1

## Schermafdrukken

![Schermafdrukken van Zola](./doc/screenshots/zola-screenshot.jpg)

## Documentatie en bronnen

- Officiele website van de app: <https://www.getzola.org/>
- Officiele beheerdersdocumentatie: <https://www.getzola.org/documentation/getting-started/overview/>
- Upstream app codedepot: <https://github.com/getzola/zola>
- YunoHost-store: <https://apps.yunohost.org/app/zola>
- Meld een bug: <https://github.com/YunoHost-Apps/zola_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/zola_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
of
sudo yunohost app upgrade zola -u https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
