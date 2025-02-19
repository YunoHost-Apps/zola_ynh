<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Zola

[![集成程度](https://apps.yunohost.org/badge/integration/zola)](https://ci-apps.yunohost.org/ci/apps/zola/)
![工作状态](https://apps.yunohost.org/badge/state/zola)
![维护状态](https://apps.yunohost.org/badge/maintained/zola)

[![使用 YunoHost 安装 Zola](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=zola)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Zola。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Zola is a [Static Site Generator](https://en.wikipedia.org/wiki/Static_site_generator).

With this package, Zola will automatically regenerate ([using Systemd Path Units](https://www.putorius.net/systemd-path-units.html)) your website if any change is made to your sources.


**分发版本：** 0.20.0~ynh1

## 截图

![Zola 的截图](./doc/screenshots/zola-screenshot.jpg)

## 文档与资源

- 官方应用网站： <https://www.getzola.org/>
- 官方管理文档： <https://www.getzola.org/documentation/getting-started/overview/>
- 上游应用代码库： <https://github.com/getzola/zola>
- YunoHost 商店： <https://apps.yunohost.org/app/zola>
- 报告 bug： <https://github.com/YunoHost-Apps/zola_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/zola_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
或
sudo yunohost app upgrade zola -u https://github.com/YunoHost-Apps/zola_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
