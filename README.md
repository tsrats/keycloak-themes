# keycloak-themes
Themes for Keycloak!

To add the theme to Keycloak, either put the files in to `/opt/keycloak/themes`, or build a `.jar` file by modifying [keycloak-themes.json](https://github.com/tsrats/keycloak-themes/blob/main/content/META-INF/keycloak-themes.json) and running `jar -cf <filename>.jar *` in the content directory. Then, add the `.jar` to `/opt/keycloak/providers` and rebuild Keycloak.

[Keycloak Documentation](https://www.keycloak.org/docs/latest/server_development/index.html#_themes)