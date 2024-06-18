<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Zola YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/zola.svg)](https://dash.yunohost.org/appci/app/zola) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/zola.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/zola.maintain.svg)

[![Instalatu Zola YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zola)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Zola YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Zola is a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator).

With this package, Zola will automatically regenerate ([using Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) your website if any change is made to your sources.


**Paketatutako bertsioa:** 0.18.0~ynh2

## Pantaila-argazkiak

![Zola(r)en pantaila-argazkia](./doc/screenshots/zola-screenshot.jpg)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://www.getzola.org/>
- Administratzaileen dokumentazio ofiziala: <https://www.getzola.org/documentation/getting-started/overview/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/getzola/zola>
- YunoHost Denda: <https://apps.yunohost.org/app/zola>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/zola_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/zola_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
edo
sudo yunohost app upgrade zola -u https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
