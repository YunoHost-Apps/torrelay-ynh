<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Tor relay for YunoHost

[![Integration level](https://apps.yunohost.org/badge/integration/torrelay)](https://ci-apps.yunohost.org/ci/apps/torrelay/)
![Working status](https://apps.yunohost.org/badge/state/torrelay)
![Maintenance status](https://apps.yunohost.org/badge/maintained/torrelay)

[![Install Tor relay with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=torrelay)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install Tor relay quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

The Tor network relies on volunteers to donate bandwidth. The more people who run relays, the better the Tor network will be. The current Tor network is quite small compared to the number of people who need to use Tor, which means we need more dedicated volunteers like you to run relays.

**Shipped version:** 0.4.8.12~ynh1
## Documentation and resources

- Official app website: <https://www.torproject.org/>
- Official admin documentation: <https://community.torproject.org/relay/setup/bridge/debian-ubuntu/>
- Upstream app code repository: <https://github.com/torproject/tor>
- YunoHost Store: <https://apps.yunohost.org/app/torrelay>
- Report a bug: <https://github.com/YunoHost-Apps/torrelay_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing --debug
or
sudo yunohost app upgrade torrelay -u https://github.com/YunoHost-Apps/torrelay_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
