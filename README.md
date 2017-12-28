# BioProcessor
This is a mod for the PC version of the game Farming Simulator 17.

It is a factory which takes digestate, liquid manure or manure input and produces fertilizer, liquid fertilizer and fuel.
        
300K digestate, liquid manure or manure produces 120K fertilizer, 120K liquid fertilizer and 60K fuel in 24 hours (5000 per hour).

* Make sure your Farming Simulator 17 PC installation has the latest patch installed
* Use universal kotte tanker trailers for optional supported hose connection
* Fill fertilizer spreaders and sprayers directly
* Silo trigger has motion sensing lighting at night, and a guide light for fill point
* Cannot refuel vehicles directly. Fill tanker trailer and refuel from the tanker trailer. This is because selling a placeable with a TankTrigger causes errors in the game.
* To customize, extract zip, open bioProcessor.i3d in Windows Notepad (using the Giants Editor is not necessary to customize these values), save changes and put back in zip:
  * change ProduktPerHour value to change production speed
  * change "capacity" values to change capacities
  * change fillLitersPerSecond value to change fill speed of fertilizer pipe
  * open bioProcessor.xml and change "dailyUpkeep" and "price" to your preference
  * will only work in multiplayer if all players have the exact same version of zip file
  * tested in a map with mCompany Sawmill also installed and no errors were found

## Credits
* Models, prefabs: Giants, Dorset, Al-Modding.
* Silo trigger light marker concept: GTX Mods
* FabrikScript, Additional Triggers: kevink98, marhu
