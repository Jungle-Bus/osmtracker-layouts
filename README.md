# osmtracker-layouts
This is a repository to host custom layouts for [OSMTracker](https://github.com/labexp/osmtracker-android) about public transport.

## Configuration

To add these layouts to OSMTracker application:
* `Settings` > `Buttons presets`
* click on the `+` symbol at the top of the screen
* then click on the wrench :wrench: at the top of the screen
* select `Custom` and add the following values in the form:
    * github username : `Jungle-Bus`
    * repository name : `osmtracker-layouts`
    * branch name : `master`
* hit `SAVE`
* Choose the layout you want to use, and download it

Once you have set up and download a layout, it is available for use : you can activate it with `Settings` > `Buttons preset`  when you are tracking.

*French version:*
Pour ajouter ces dispositions dans l'application OSMTracker:
* dans `Paramètres` > `Boutons`, appuyer sur `+` en haut à droite
* appuyer ensuite sur la clef :wrench: en haut à droite
* cliquer sur `custom`, et renseigner les valeurs suivantes dans le formulaire de configuration :
  * github username : `Jungle-Bus`
  * repository name : `osmtracker-layouts`
  * branch name : `master`
* Sauvegarder
* Choisir à présent une disposition à ajouter à l'application, et la télécharger

Cette disposition est maintenant disponible dans la liste des dispositions, dans `Paramètres` > `Boutons`. Vous pouvez l'activer quand c'est nécessaire ;)

## List of layouts
### Bus route
![Image of layout](layouts/bus_route/layout.png)

### Bus route with occupancy
![Image of layout](layouts/bus_route_occupancy/layout.png)

### Ferry route
![Image of layout](layouts/ferry_route/layout.png)

## Translate

Let's say you want to translate the bus route layout in your language, you will need to do the following:
- add a line with your language and a description in the [metadata file](https://github.com/Jungle-Bus/osmtracker-layouts/blob/master/layouts/metadata/bus_route.xml)
- duplicate the [en.xml file](https://github.com/Jungle-Bus/osmtracker-layouts/blob/master/layouts/bus_route/en.xml) and translate the `label` items

## See also

Once you have collected your tracks, you can use JOSM with the [Jungle stop presets](https://github.com/Jungle-Bus/josm-presets) to quickly create the route in OpenStreetMap :wink:

![jungle stop presets](https://raw.githubusercontent.com/Jungle-Bus/josm-presets/master/doc/josm_capture_menu.png)

## Credits

This project has been developed by the [Jungle Bus](http://junglebus.io/) team.

The code in this repository is under the GPL-3.0 license.

The rickshaw icon was created by James Fenton from the Noun Project. The taxi icon was created by Andi Nur Abdillah from the Noun Project.

If you value this work, show your support by donating to the [OSM French local chapter](http://openstreetmap.fr).

![Jungle Bus Logo](https://i.imgur.com/7QskztK.png)
