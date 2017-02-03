#  CustomArkLootDrops

_Improved default world beacons for hosted [ARK: Survival Evolved](https://www.youtube.com/survivetheark) servers._  
* This is designed for PC servers. Sorry XBOX and PS4 players, it's nothing personal, I just only play PC.
* Designed with **Balance** in mind. I listen to feedback and update this code accordingly. If you noticed unbalanced things let me know.
* Non-invasive to your server, nothing to install.

## HOW TO USE TO YOUR SERVER  
1. Copy Data to Clipboard.  
  * **The Island/The Center/Normal Maps**: Copy all the code from the file [Standard/FULL_DEPLOY_CODE](Standard/FULL_DEPLOY_CODE)  
    * - [raw standard code link](https://raw.githubusercontent.com/bytePro17124/CustomArkLootDrops/master/Standard/FULL_DEPLOY_CODE)
  * **Scorched Earth Map**: Copy all the code from the file [ScorchedEarth/FULL_DEPLOY_CODE](ScorchedEarth/FULL_DEPLOY_CODE)  
    * - [raw se code link](https://raw.githubusercontent.com/bytePro17124/CustomArkLootDrops/master/ScorchedEarth/FULL_DEPLOY_CODE)  
2. Paste the copied text into your *game.ini* file, anywhere under the [/script/shootergame.shootergamemode] header. If you are using ArkServerManager, there is paste in code button you can use.
3. Reboot. The Beacons will be updated the next time your server boots up.  

Note: If the beacons didn't seem to apply, be sure you are copying all of the text, and be sure you are pasting into the correct game.ini file.

## The Goal  
The goal with this drop rework is to improve the Default World Beacon crates in ARK: Survival Evolved, and focus on balancing for what would really make sense, while aiming to not make the drops overpowered. This code should improve the usefulness and excitement  of hunting for beacons.  The rare promise of truly unexpected finds will keep players coming back.

## How are these new beacons different?  
They are (way) more filled out. **All** the previously left out items have been added with the exception that any items found in Deep Sea loot crates (except in ScorchedEarth where the sea crates are redone). In general, items are grouped into the beacon close to the Engram Level. Rarity and odds are carefully balanced to make the best or most expensive items most rare, and explosives always in low quantities.  

Items with Quality Ratings (Weapons, Armor, Saddles) drop individual pieces or patterns and are scaled up slightly in Double Crates (they have rings on them). Finding extremely high quality pieces is very rare on a server 4 difficulty. This rarity scales up or down along with game server difficulty as normal.

## Support  
*If you've found these useful, please consider donating to keep this project alive.*
* [PayPal](https://www.paypal.me/mattearly/)  
* Bitcoin: 1Nwi1GBJtsuo1WQJqK83Ckr5NDJ3zwi5mM  
* Total Donations: $0  
  
### Make your own versions  
Fork or Download then Edit the code for the beacons. After editing, run the **compile_code** powershell script (most versions of Windows will do this as far as I know) to turn it into Full Deploy Code. To learn more about editing beacons, Google is your best friend. There is a lot of useful information out there. If you look at the broken down, syntaxed code on my Github it will probably begin to make sense.

### TODO  
BOTH  
- [ ] Add Archaeopteryx Egg - spawn code: PrimalItemConsumable_Egg_Archa_C
- [ ] Add Therizinosaurus Egg - spawn code: waiting on wiki to update with spawn code
- [ ] Add Sweet Vegetable Cake - spawn code: PrimalItemConsumable_SweetVeggieCake_C
- [ ] Add Bio Toxin - spawn code: waiting on wiki to update with spawn code
- [ ] Add Megalosaurus Egg - spawn code: PrimalItemConsumable_Egg_Megalosaurus_C
- [ ] Add Tapejara Egg - spawn code: PrimalItemConsumable_Egg_Tapejara_C
- [ ] Add Moschops Egg - spawn code: PrimalItemConsumable_Egg_Moschops_C
- [ ] Add Beer Jar - spawn code: PrimalItemConsumable_BeerJar_C
- [ ] Element Resource system
- [ ] Tek Replicator
- [ ] Tek Rifle
- [ ] Tek Helmet
- [ ] Tek Visor
- [ ] Tek Jetpack
- [ ] Tek Boots
- [ ] Tek Gloves
- [ ] Tek Rex Saddle
- [ ] Tek Transmitter
- [ ] and more.
- [ ] New Dino: Ovis Aries!
- [ ] New Dino: Purlovia!
- [ ] Scissors
  
STANDARD ONLY  
- [ ] Add Pachyrhino Egg - spawn code: PrimalItemConsumable_Egg_Pachyrhino_C
- [ ] Add Kaprosuchus Egg - spawn code: PrimalItemConsumable_Egg_Kaprosuchus_C
- [ ] Add Troodon Egg - spawn code: PrimalItemConsumable_Egg_Troodon_C
- [ ] Add Pegomastax Egg - spawn code: PrimalItemConsumable_Egg_Pegomastax_C

  
  
SCORCHED EARTH ONLY  