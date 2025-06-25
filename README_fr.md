# Waterbear pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/waterbear.svg)](https://dash.yunohost.org/appci/app/waterbear) ![](https://ci-apps.yunohost.org/ci/badges/waterbear.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/waterbear.maintain.svg)  
[![Installer Waterbear avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=waterbear)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Waterbear rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Waterbear est un logiciel de gestion de bibliothèque à installer sur un serveur web (type Apache), PHP et MySQL. Il est full-web, ce qui signifie qu'il est accessible uniquement depuis un navigateur web. Il permet d'assurer les fonctions essentielles d'une bibliothèque ou d'un centre de documentation :

### Features

- Catalogage,
- prêt, retours et réservations,
- transit,
- import/export unimarc,
- échanges avec la Bibliothèque De Prêt,
- revues (périodiques),
- acquisitions,
- statistiques

Il est possible d'ajouter un catalogue en ligne (OPAC) afin de permettre aux utilisateurs d'interroger le catalogue, consulter leur compte lecteur, diffuser de l'information, etc.
L'OPAC recommandé est [Bokeh](https://www.bokeh-library-portal.org/) mais d'autres logiciels sont possibles.


**Version incluse :** 25.02.2021~ynh1



## Captures d'écran

![](./doc/screenshots/example.jpg)

## Avertissements / informations importantes

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentations et ressources

* Site officiel de l'app : waterbear.info/
* Documentation officielle utilisateur : https://indexmailwaterbear.wordpress.com/
* Documentation officielle de l'admin : http://waterbear.info/doc/doc.php
* Documentation YunoHost pour cette app : https://yunohost.org/app_waterbear
* Signaler un bug : https://github.com/YunoHost-Apps/waterbear_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/waterbear_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/waterbear_ynh/tree/testing --debug
ou
sudo yunohost app upgrade waterbear -u https://github.com/YunoHost-Apps/waterbear_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps