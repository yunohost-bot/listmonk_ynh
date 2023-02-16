<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Listmonk for YunoHost

[![Integration level](https://dash.yunohost.org/integration/listmonk.svg)](https://dash.yunohost.org/appci/app/listmonk) ![Working status](https://ci-apps.yunohost.org/ci/badges/listmonk.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/listmonk.maintain.svg)

[![Install Listmonk with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=listmonk)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Listmonk quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Listmonk is a standalone, self-hosted, newsletter and mailing list manager. It is fast, feature-rich, and packed into a single binary. It uses a PostgreSQL (⩾ v9.4) database as its data store.


**Shipped version:** 2.3.0~ynh3

**Demo:** https://demo.listmonk.app/

## Screenshots

![Screenshot of Listmonk](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://listmonk.app/>
* Official admin documentation: <https://listmonk.app/docs/>
* Upstream app code repository: <https://github.com/knadh/listmonk>
* YunoHost documentation for this app: <https://yunohost.org/app_listmonk>
* Report a bug: <https://github.com/YunoHost-Apps/listmonk_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/listmonk_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/listmonk_ynh/tree/testing --debug
or
sudo yunohost app upgrade listmonk -u https://github.com/YunoHost-Apps/listmonk_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
