# StarCraft II Agent #

### Description ###

![picture alt](https://heise.cloudimg.io/width/610/q85.png-lossy-85.webp-lossy-85.foil1/_www-heise-de_/imgs/18/2/3/1/7/1/8/5/OHQFFPJDA5HN1508778072144-b382ee11b44ca95f-40f6d870367b7ed2.jpeg)

_The  StartCraft II Agent is an AI Bot that can effectively challenge even the most proficient players of the iconic game._

### Installation ###

1. Install [StarCraft II Client](https://starcraft2.com/en-gb/) (Windows / Mac)
2. Install [Python 3.7.X](https://www.python.org/downloads/)
3. Install [Python-sc2](https://github.com/Dentosal/python-sc2)

    `pip install sc2`

4. Download StarCraft II Maps from the maps pack section of the Blizzard s2client:
https://github.com/Blizzard/s2client-proto#map-packs
    
    * You can download all maps, or at least the [Meele Pack.](http://blzdistsc2-a.akamaihd.net/MapPacks/Melee.zip)
  
    * Extract the zip-files to the the "_Maps_" diretory within the _StarCraft II_ directory. The file structure should be something of the following form:

        `StarCraft II\Maps\Meele\Flat32.SC2Map`
        
5. Create your own bot by inheriting from _sc2.BotAI_ class:
        `class StarBot(sc2.BotAI):`

6. You can learn more about the _BotAI_ class by heading to:
`../sc2/bot_ai.py`

### Note ###
* For further help with building the AI bot, feel free to follow along the following tutorial:
https://pythonprogramming.net/starcraft-ii-ai-python-sc2-tutorial/
