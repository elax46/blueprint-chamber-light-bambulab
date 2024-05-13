[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg


## Blueprint chamber light for Bambulab 3D Printer

Every time you start printing on your bambulab printer the light turns on personally I find it annoying for this audience this Blueprint has the purpose of turning off the LED of your bambulab printer when it switches from the state in preparation to runnig.

### Bambulab printer on Home Assistant

To be able to use this automation it is essential that you have imported your bambulab printer into your home assistant. For this you need an integration that can be installed via [HACS](https://hacs.xyz/docs/setup/download/)

 - [A Home Assistant Integration for Bambu Lab printers](https://github.com/greghesp/ha-bambulab)
 - [Bambulab Home Assistant Dashboards](https://www.wolfwithsword.com/bambulab-home-assistant-dashboard/)

### Installation

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/elax46/blueprint-chamber-light-bambulab/blob/main/blueprints/automation/bambulab/turn_off_printer_light.yaml)

### Note

It could happen that if you start a print from the micro SD and not from the Bambu Handy printing history, if the printer status sensor does not switch from ``preparing`` to ``running`` the light will not go off.

Feel free to share/edit this project to discuss I refer you to the topic on the home assistant forum

- [Home Assistant Forum Topic](https://community.home-assistant.io/t/chamber-light-for-bambulab-3d-printer/728721)

## Other projects

If you need custom icons for your home assistant I recommend you take a look at this project

- [Custom Brand Icons](https://github.com/elax46/custom-brand-icons)