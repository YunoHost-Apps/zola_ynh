- Votre Zola est installé dans `__INSTALL_DIR__`
- Votre contenu doit être dans `__INSTALL_DIR__/content`
- Votre fichier de configuration est `__INSTALL_DIR__/config.toml` (voir [la doc de configuration](https://www.getzola.org/documentation/getting-started/configuration/))
- [Choisissez un thème](https://www.getzola.org/themes/), installez-le dans `__INSTALL_DIR__/themes`, puis configurez-le dans votre fichier `config.toml`.
- Le site sera automatiquement mis à jour à chaque fois que vous modifierez quelque chose dans les dossiers `content`, `static`, `templates` ou `themes` ou le fichier `config.toml` !

Si vous avez besoin de générer le site à la main, veuillez utiliser cette commande : `sudo -u __APP__ -g www-data __INSTALL_DIR__/zola build`

Si votre site affiche une erreur 403, veuillez corriger les permissions à l'aide de cette commande : `chown -R zola:www-data __INSTALL_DIR__`
