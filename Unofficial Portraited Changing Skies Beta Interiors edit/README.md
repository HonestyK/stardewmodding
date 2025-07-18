# Unofficial Portraited Changing Skies Beta Interiors edit

## This repository is uploaded for the purposes of demonstrating a usable fix for the **[Portraited Changing Skies Interiors](https://www.nexusmods.com/stardewvalley/mods/30002)** since it was missing some folders and json files. DO NOT UPLOAD THIS FOR PERSONAL USE.

### How it works:

This fix uses a different method from the original content.js file. 

Rather than request external code from jsons in different folders, I made it so that there's a token with a list of all locations that currently have a recolor folder and then used a conditional to tell the file whether to use the default weather backgrounds or the recolor ones. This method will have issues if the recolors will have different amount of assets--it assumes that all recolors have the exact same locations so placeholders should be used--but it should still keep working while showing no backgrounds for the invalid cases.
