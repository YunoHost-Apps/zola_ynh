<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Zola untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/zola.svg)](https://ci-apps.yunohost.org/ci/apps/zola/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/zola.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/zola.maintain.svg)

[![Pasang Zola dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zola)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Zola secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Zola is a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator).

With this package, Zola will automatically regenerate ([using Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) your website if any change is made to your sources.


**Versi terkirim:** 0.19.2~ynh2

## Tangkapan Layar

![Tangkapan Layar pada Zola](./doc/screenshots/zola-screenshot.jpg)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://www.getzola.org/>
- Dokumentasi admin resmi: <https://www.getzola.org/documentation/getting-started/overview/>
- Depot kode aplikasi hulu: <https://github.com/getzola/zola>
- Gudang YunoHost: <https://apps.yunohost.org/app/zola>
- Laporkan bug: <https://github.com/YunoHost-Apps/zola_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/zola_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
atau
sudo yunohost app upgrade zola -u https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
