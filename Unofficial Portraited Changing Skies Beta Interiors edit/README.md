# Unofficial Portraited Changing Skies Beta Interiors edit

A fix to make **[Portraited Changing Skies Interiors](https://www.nexusmods.com/stardewvalley/mods/30002)** work with **[Portraited Changing Skies - Stable](https://www.nexusmods.com/stardewvalley/mods/23337)** since it was missing some folders and json files.
---

### How it works:
This fix is basically just a copy of **Portraited Changing Skies - Stable** with my edited content.js and the art assets from **Portraited Changing Skies Interiors** added in.

Currently this fix only works for Vanilla and Earthy because they're the only ones with any art assets right now. Note that both of these recolors are using the exact same art for each location so there's no difference between Vanilla and Earthy.

The only locations that this will add backgrounds to are: Blacksmith, JojaMart, WizardTower, Museum, Pierre's, and the Saloon.

This fix uses a different method from the original content.js file. 

Rather than request external code from jsons in different folders, I made it so that there's a token with a list of all locations that currently have a recolor folder and then used a conditional to tell the file whether to use the default weather backgrounds or the recolor ones. This method will have issues if the recolors will have different amount of assets--it assumes that all recolors have the exact same locations so placeholders should be used--but it should still keep working while showing no backgrounds for the invalid cases.

---

### How to use:
Delete the mod folder for **Portraited Changing Skies - Stable** and replace it with this one. Also give the folder a shorter name as there may be errors if the folder or file name is too long.

---

This repository will be taken down if requested or when it's not needed anymore.
