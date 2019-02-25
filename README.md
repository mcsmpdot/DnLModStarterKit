# DnLModStarterKit
This starter kit is intended to help people make mods for the game Dark and Light.

In order to put objects on the map or in a players inventory automatically you have to cook your mod as a map extension.

The actor DnLPlacementManager is placed on the map by the the map extension file DnLPlacementLevel. Be sure this file is place in the directory Maps\TheIslandSubMaps and not in your mods mod folder.

When placing an item in the players inventory consider using a blueprint only item which would allow them to craft your item.

If you have more then one item that the player can craft consider making a workbench that crafts those items.

While an engram file is provided the game does not currently rely on them.

As placement of buildable objects in the environment is buggy I have included a system that you can use to place objects.

The placement system is for simple placeable items. You will need to enhance this if you want to place structures that need to snap or link together.
