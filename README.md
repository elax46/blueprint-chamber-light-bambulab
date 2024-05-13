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

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=)

### Note

It could happen that if you start a print from the micro SD and not from the Bambu Handy printing history, if the printer status sensor does not switch from ``preparing`` to ``running`` the light will not go off.