<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Zola для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/zola)](https://ci-apps.yunohost.org/ci/apps/zola/)
![Состояние работы](https://apps.yunohost.org/badge/state/zola)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/zola)

[![Установите Zola с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zola)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Zola быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

Zola is a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator).

With this package, Zola will automatically regenerate ([using Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) your website if any change is made to your sources.


**Поставляемая версия:** 0.20.0~ynh1

## Снимки экрана

![Снимок экрана Zola](./doc/screenshots/zola-screenshot.jpg)

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://www.getzola.org/>
- Официальная документация администратора: <https://www.getzola.org/documentation/getting-started/overview/>
- Репозиторий кода главной ветки приложения: <https://github.com/getzola/zola>
- Магазин YunoHost: <https://apps.yunohost.org/app/zola>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/zola_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/zola_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
или
sudo yunohost app upgrade zola -u https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
