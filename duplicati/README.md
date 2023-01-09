# Home Assistant Add-on: Duplicati backup

_Allow Duplicati off-site backups of HA containers_

![Supports amd64 Architecture][amd64-shield]

[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg

## Brief installation instructions

- Read the [HA docs on creating a local addon](https://developers.home-assistant.io/docs/add-ons/) and try out the Hello World tutorial there.
- Clone the repo [https://github.com/hunterdrayman/HA-Addons/duplicati](https://github.com/hunterdrayman/HA-Addons/tree/main/duplicati) into the addons directory which is located at the same level as the HA config folder.
- Make local changes e.g. Timezone and architecture (UK time and AMD64 assumed).
- Restart HA and go to Settings-&gt;Add-ons-&gt;Add on Store
- Click **Check for Updates** in the top-right drop-down menu
- Install
- Go to the Duplicati web interface your HA host port 8200