# FloridaMan's Home Assistant Addons

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Ffloridaman7588%2Fhass-addons) 

![GitHub](https://img.shields.io/github/license/FloridaMan7588/hass-addons)

These are a few addons I maintain (see warning) mostly based off of other software that I haven't wrote because I'm a bit of a dunce and don't write a lot of good code. I'm still learning :). Anyway, this repository is just where the addons are published, each addon has it's own repository for it's code, CI/CD, and issue reports. DO NOT REPORT ISSUES HERE (unless it is to do with the publishing pipeline)!

# WARNING/DISCLAIMER
Please do not use this software if you depend on it, I maintain it the bear minimum for this to not be abandonware. If you want production ready software, look elsewhere. As I said, I am a dunce. I am not liable if you install this and your system breaks, although by the nature of HA it shouldn't. 

# Adding the repository
To add this repository for the installation of these addons, you must be running a supported installation of Home Assistant Supervised. Supervised enables the Addons menu in Settings, if you do not see this menu, your installation may not be supported. 
If you have ``my.home-assistant.io` set up, you can click the badge at the top of the repository.
To add the repository, navigate to 

``Settings > Add-ons > Add-on Store > Three dots menu (top right) > Repositories``

Inside the repositories menu, enter the below URL into the add field and select **Add**.

``https://github.com/floridaman7588/hass-addons``


# What's distributed in this repository

## mochad-ha-addon
The mochad-ha-addon is very small HA addon that runs the mocha daemon, a service for interacting with and controlling an X-10 branded CM15A, CM15Pro, or CM19A. 
See the [mochad-ha-addon](https://fm7588.me/mochad) repository for more details.

## silabs-cfw-ha-addon
A not very small HA addon that automatically checks for new versions of an installed (custom) firmware on an SILabs based Zigbee USB stick and allows for easy updating of the firmware.

See the [silabs-cfw-ha-addon](https://fm7588.me/silabs-cfw) repository for more details.

# Licensing

I try to license as many of my projects under the MIT license as it is short, easy to understand, and highly permissible for the end user and anyone who wishes to use my code. 
That includes this project, which is licensed under the MIT. You can see the terms in the file called LICENSE