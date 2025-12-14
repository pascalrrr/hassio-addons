# Pascalrr's Home Assistant Addons

![License](https://img.shields.io/github/license/pascalrrr/hassio-addons?style=flat-square)

This is the Home Assistant Supervisor Add-on repository for a handful of Add-ons that I've created. This repository and the repositories containing the Add-on source are intended to be structured as similarly to the [Hass.io Community Add-ons](https://github.com/hassio-addons) organization for simplicity.

## Disclaimer
Please do not use this software if you depend on it, I have very little time on my hands and so these are not greatly maintained beyond automated CI/CD. If you want production ready software, look elsewhere. I am not liable if you install Add-ons from this repository and your system breaks, although, by the nature of Home Assistant Supervisor, it shouldn't. 

## Adding the repository
To add this repository, you can either use the My Home Assistant button below, or the manual instructions that follow it.

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fpascalrrr%2Fhassio-addons) 

### Manual Steps
Navigate to **Settings > Add-ons > Add-on Store > Three dots menu (top right) > Repositories**

Inside the repositories menu, enter ``https://github.com/pascalrrr/hassio-addons`` into the add field and select **Add**.


## Add-ons

### Mochad
![Latest Version][mochad-version-shield]
![Supports aarch64 Architecture][mochad-aarch64-shield]
![Supports amd64 Architecture][mochad-amd64-shield]
![Supports armhf Architecture][mochad-armhf-shield]
![Supports armv7 Architecture][mochad-armv7-shield]
![Supports i386 Architecture][mochad-i386-shield]

The mochad-ha-addon is very small Home Assistant Add-on for the Mocha Daemon, a service for interacting with and controlling an X-10 branded CM15A, CM15Pro, or CM19A.

See the [mochad-ha-addon](https://pascalrr.gay/redirect/mochad-github) repository for more details.

### Hyperion (.ng)
![Latest Version][hyperion-version-shield]
![Supports aarch64 Architecture][hyperion-aarch64-shield]
![Supports amd64 Architecture][hyperion-amd64-shield]
![Supports armhf Architecture][hyperion-armhf-shield]
![Supports armv7 Architecture][hyperion-armv7-shield]
![Supports i386 Architecture][hyperion-i386-shield]

A Home Assistant Add-on for the Hyperion (Next Generation) ambient/bias lighting control system with Ingress support. This is still very new, but it should be able to handle most features of Hyperion.

See the [hyperion-ha-addon](https://pascalrr.gay/redirect/hyperion-github) repository for more details.

## Licensing

I try to license as many of my projects under the MIT license as it is short, easy to understand, and highly permissible for the end user and anyone who wishes to use my code. 
That includes this project, which is licensed under the MIT. You can see the terms in LICENSE.md file


[mochad-version-shield]: https://img.shields.io/badge/version-0.0.2-blue.svg?style=flat-square
[mochad-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg?style=flat-square
[mochad-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg?style=flat-square
[mochad-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg?style=flat-square
[mochad-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg?style=flat-square
[mochad-i386-shield]: https://img.shields.io/badge/i386-no-red.svg?style=flat-square
[hyperion-version-shield]: https://img.shields.io/badge/version-2.1.1-blue.svg?style=flat-square
[hyperion-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg?style=flat-square
[hyperion-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg?style=flat-square
[hyperion-armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg?style=flat-square
[hyperion-armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg?style=flat-square
[hyperion-i386-shield]: https://img.shields.io/badge/i386-no-red.svg?style=flat-square