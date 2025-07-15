- Your Zola is installed in `__INSTALL_DIR__`
- Your content should be in `__INSTALL_DIR__/content`
- Your config file is `__INSTALL_DIR__/config.toml` (see [config docs](https://www.getzola.org/documentation/getting-started/configuration/))
- [Choose a theme](https://www.getzola.org/themes/), install it in `__INSTALL_DIR__/themes`, then configure it in your `config.toml` file
- The website will be automatically updated each time you modify something inside the `content`, `static`, `templates` or `themes` folders or the `config.toml` file!

If you have to manually launch the site build, use the following command: `sudo -u __APP__ __INSTALL_DIR__/zola build`

If your website shows a 403 error, please fix the permissions using this command: `chown -R zola:www-data __INSTALL_DIR__`
