# OoTRMapTracker

## Content

This is a pack for [EmoTracker](https://emotracker.net/) designed for the [Ocarina of Time Randomizer](https://ootrandomizer.com/).
You can easily download it from within the EmoTracker application.

This pack allows you to keep track of your current item loadout and has maps with all item locations for child and adult Link. These locations get filtered by your current item loadout to only show what you can actually reach.

## Questions

If you have any questions regarding the pack or the tracker itself, I recommend joining the [EmoTracker discord](https://emotracker.net/community/) and asking in there. Or you can just send me a DM on Discord to __Hamsda#4585__ or open an issue on Github.

## Variants

The pack offers 7 different variants:

1. Map Tracker
2. Map Tracker (Keysanity)
3. Items Only
4. Items Only (Keysanity)
5. Items Only (minimal)
6. Entrance Randomizer
7. Entrance Randomizer (Keysanity)

## Vanilla vs Master Quest Dungeons

The Randomizer has the option to switch some or all dungeons to their Master Quest equivalents.  
To accomodate for this, you can click on the dungeon labels to change them from vanilla ![vanilla deku](ootrando_overworldmap_hamsda/images/label_deku.png) to Master Quest ![mq deku](ootrando_overworldmap_hamsda/images/label_deku_mq.png). You can use this in the non map variants as a reminder.
The small key maximum amounts in the keysanity variants will dynamically update according to what you selected for the corresponding dungeon.

## Special items

Some of this functionality might not be immediately obvious:

- Right clicking ![Fairy Ocarina](ootrando_overworldmap_hamsda/images/fairyocarina.png "Fairy Ocarina")/![Ocarina of Time](ootrando_overworldmap_hamsda/images/ocarina.png "Ocarina of Time") will overlay it with ![Scarecrow](ootrando_overworldmap_hamsda/images/overlay_scarecrow.png "Scarecrow"), indicating that you have confirmed the scarecrow song or started with free scarecrow. Locations that make use of the scarecrow will show up as sequence breaks unless this is turned on.
- ![Ice Trap](ootrando_overworldmap_hamsda/images/icetrap.png "Ice Trap") is used as a counter for ice traps. This is somewhat useful to evaluate freestanding items during racing, but mostly just for fun with settings that include higher numbers of ice traps.

## Settings (for map variants)

There is a variety of settings available to accomodate the different options that the Randomizer offers:

### Forest

This setting determines if you can leave the Kokiri Forest without beating the Deku Tree ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Main_Rules)).

- ![Closed Forest](ootrando_overworldmap_hamsda/images/setting_forest_closed.png "Closed Forest") You will find the Kokiri Sword and Slingshot early on to beat the Deku Tree before leaving Kokiri Forest.
- ![Closed Deku](ootrando_overworldmap_hamsda/images/setting_forest_deku.png "Closed Deku") You can leave Kokiri Forest but will need the Kokiri Sword and Deku Shield to go to the Deku Tree.
- ![Open Forest](ootrando_overworldmap_hamsda/images/setting_forest_open.png "Open Forest") You can immediately leave Kokiri Forest and go to the Deku Tree.

### Door of Time

This setting determines whether the Door of Time starts open or closed ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Main_Rules)).

- ![Closed Door](ootrando_overworldmap_hamsda/images/setting_door_closed.png "Closed Door") You will find the Song of Time as a child to open the Door of Time.
- ![Open Door](ootrando_overworldmap_hamsda/images/setting_door_open.png "Open Door") The Door of Time starts open and you can immediately go adult.

### Zoras Fountain

This setting determines whether Zoras Fountain starts open or closed ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Main_Rules)).

- ![Closed Fountain](ootrando_overworldmap_hamsda/images/setting_fountain_closed.png "Closed Fountain") You can find Rutos Letter and open Zoras Fountain by moving King Zora.
- ![Open Fountain](ootrando_overworldmap_hamsda/images/setting_fountain_open.png "Open Fountain") Rutos Letter can no longer be found, but Zoras Fountain can be accessed without moving King Zora.

### Gerudo Fortress

This setting determines the state of the ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Main_Rules)).

- ![Normal Gerudo Fortress](ootrando_overworldmap_hamsda/images/setting_gerudo_fortress_normal.png "Normal Gerudo Fortress") You will have to rescue all 4 carpenters.
- ![Fast Gerudo Fortress](ootrando_overworldmap_hamsda/images/setting_gerudo_fortress_fast.png "Fast Gerudo Fortress") You only need to free one carpenter (F1 North).
- ![Open Gerudo Fortress](ootrando_overworldmap_hamsda/images/setting_gerudo_fortress_open.png "Open Gerudo Fortress") The carpenters start free and the Fortress is immediately accessible (if `Shuffle Gerudo Card` is turned off, mark your ![Gerudo Card](ootrando_overworldmap_hamsda/images/gerudocard.png "Open Gerudo Fortress") as well).

### Rainbow Bridge

This setting determines what is needed to trigger the rainbow bridge in front of Ganons castle ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Main_Rules)).

- ![Always Open](ootrando_overworldmap_hamsda/images/setting_bridge_open.png "Always Open") Nothing required, bridge is always open
- ![Vanilla](ootrando_overworldmap_hamsda/images/setting_bridge_vanilla.png "Vanilla") Light arrows, shadow medallion, and spirit medallion required
- ![All Stones](ootrando_overworldmap_hamsda/images/setting_bridge_stones.png "All Stones") All 3 stones required
- ![All Medallions](ootrando_overworldmap_hamsda/images/setting_bridge_medallions.png "All Medallions") All 6 medallions required
- ![All Dungeons](ootrando_overworldmap_hamsda/images/setting_bridge_dungeons.png "All Dungeons") All 6 medallions and 3 stones required
- ![100 GS tokens](ootrando_overworldmap_hamsda/images/setting_bridge_100gs.png "100 GS tokens") 100 gold skulltula tokens required

### Shuffle Kokiri Sword

This setting determines if the Kokiri Sword gets shuffled ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Main_Rules)).

- ![Kokiri Sword not shuffled](ootrando_overworldmap_hamsda/images/setting_shuffle_sword1_no.png "Kokiri Sword not shuffled") The Kokiri Sword is not shuffled and will be captured in the corresponding chest by default.
- ![Kokiri Sword shuffled](ootrando_overworldmap_hamsda/images/setting_shuffle_sword1_yes.png "Kokiri Sword shuffled") The Kokiri Sword is shuffled into the item pool and will not be captured.

### Shuffle Ocarinas

This setting determines if the Ocarinas get shuffled ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Main_Rules)).

- ![Ocarinas not shuffled](ootrando_overworldmap_hamsda/images/setting_shuffle_ocarinas_no.png "Ocarinas not shuffled") The Ocarinas are not shuffled and will be captured in the corresponding chests by default.
- ![Ocarinas shuffled](ootrando_overworldmap_hamsda/images/setting_shuffle_ocarinas_yes.png "Ocarinas shuffled") The Ocarinas are shuffled into the item pool and will not be captured.

### Shuffle Weird Egg

This setting determines if the Weird Egg gets shuffled ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Main_Rules)).

- ![Weird Egg not shuffled](ootrando_overworldmap_hamsda/images/setting_shuffle_egg_no.png "Weird Egg not shuffled") The Weird Egg is not shuffled and will be captured in the corresponding chest by default.
- ![Weird Egg shuffled](ootrando_overworldmap_hamsda/images/setting_shuffle_egg_yes.png "Weird Egg shuffled") The Weird Egg is shuffled into the item pool and will not be captured.

### Shuffle Gerudo Card

This setting determines if the Gerudo Card gets shuffled ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Main_Rules)).

- ![Gerudo Card not shuffled](ootrando_overworldmap_hamsda/images/setting_shuffle_card_no.png "Gerudo Card not shuffled") The Gerudo Card is not shuffled and will be captured in the corresponding chest by default.
- ![Gerudo Card shuffled](ootrando_overworldmap_hamsda/images/setting_shuffle_card_yes.png "Gerudo Card shuffled") The Gerudo Card is shuffled into the item pool and will not be captured.

### Shuffle Magic Beans

This setting determines if Magic Beans are shuffled.

- ![Magic Beans not shuffled](ootrando_overworldmap_hamsda/images/setting_shuffle_beans_no.png "Magic Beans not shuffled") Magic Beans are not shuffled and will be captured in the corresponding chest by default.
- ![Magic Beans shuffled](ootrando_overworldmap_hamsda/images/setting_shuffle_beans_yes.png "Magic Beans shuffled") The Magic Beans are shuffled into the item pool and will not be captured.

### Shuffle Deku Scrubs

This setting determines if all Deku Scrubs have randomized items ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Main_Rules)).

- ![Scrubs not shuffled](ootrando_overworldmap_hamsda/images/setting_scrub_shuffle_no.png "Scrubs not shuffled") Only the three Deku Scrubs that give actual items in the vanilla game can have random items.
- ![Scrubs shuffled](ootrando_overworldmap_hamsda/images/setting_scrub_shuffle_yes.png "Scrubs shuffled") All Deku Scrubs can have random items.

### Shopsanity

This setting determines if Shopsanity is active ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Main_Rules)).

- ![Shopsanity off](ootrando_overworldmap_hamsda/images/setting_shopsanity_no.png "Shopsanity off") The shops have their regular items.
- ![Shopsanity on](ootrando_overworldmap_hamsda/images/setting_shopsanity_yes.png "Shopsanity on") A varying amount of items in the shops is randomized.

### Cowsanity

This setting determines if Cowsanity is active.

- ![Cowsanity off](ootrando_overworldmap_hamsda/images/setting_cowsanity_no.png "Cowsanity off") The cows just give milk when Eponas song gets played.
- ![Cowsanity on](ootrando_overworldmap_hamsda/images/setting_cowsanity_yes.png "Cowsanity on") The cows will give a random item the first time Eponas song gets played.

### Gold Skulltulas

This setting determines which Gold Skulltulas are shown (especially useful for [Tokensanity](https://wiki.ootrandomizer.com/index.php?title=Readme#Main_Rules)).

- ![Skulltulas hidden](ootrando_overworldmap_hamsda/images/setting_skulltulas_off.png "Skulltulas hidden") Gold Skulltulas will be hidden.
- ![Skulltulas in dungeons](ootrando_overworldmap_hamsda/images/setting_skulltulas_dungeons.png "Skulltulas in dungeons") The Gold Skulltulas in dungeons will be displayed.
- ![Skulltulas everywhere](ootrando_overworldmap_hamsda/images/setting_skulltulas_all.png "Skulltulas everywhere") All Gold Skulltulas will be displayed.

### Bombchus in logic

This setting determines if Bombchus are considered by the logic ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Main_Rules)).

- ![Bombchus not in logic](ootrando_overworldmap_hamsda/images/setting_logic_chus_no.png "Bombchus not in logic") Bombchus will never be considered by the logic and can be used to sequence break bomb locations.
- ![Bombchus in logic](ootrando_overworldmap_hamsda/images/setting_logic_chus_yes.png "Bombchus in logic") Bombchus can be used as regular explosives like bombs in logic.

### Lens of Truth

This setting changes where the logic requires the Lens of Truth ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Detailed_Logic)).

- ![Required everywhere](ootrando_overworldmap_hamsda/images/setting_lens_all.png "Required everywhere") Required to see all invisible things.
- ![Wasteland and Chest Minigame](ootrando_overworldmap_hamsda/images/setting_lens_wasteland.png "Wasteland and Chest Minigame") Required to cross the Haunted Wasteland and to win the Treasure Chest minigame.
- ![Only Chest Minigame](ootrando_overworldmap_hamsda/images/setting_lens_chest.png "Only Chest Minigame") Required only to win the Treasure Chest minigame.

### Fewer Tunic Requirements

This setting changes where the logic requires Goron and Zora tunics ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Detailed_Logic)).

- ![Required everywhere](ootrando_overworldmap_hamsda/images/setting_fewer_tunics_no.png "Required everywhere") Required basically everywhere a heat/breath timer shows up.
- ![Fewer requirements](ootrando_overworldmap_hamsda/images/setting_fewer_tunics_yes.png "Fewer requirements") Required for fewer locations.

### Hints

This setting determines when hintable locations will show up on the map ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Readme#Other)).

- ![Hints off](ootrando_overworldmap_hamsda/images/setting_hints_off.png "Hints off") Hintable locations will never show up on the map.
- ![Hints Truth](ootrando_overworldmap_hamsda/images/setting_hints_truth.png "Hints Truth") Hintable locations will show up on the map if you have ![Mask of Truth](ootrando_overworldmap_hamsda/images/truth.png "Mask of Truth").
- ![Hints Agony](ootrando_overworldmap_hamsda/images/setting_hints_agony.png "Hints Agony") Hintable locations will show up on the map if you have ![Stone of Agony](ootrando_overworldmap_hamsda/images/agony.png "Stone of Agony").
- ![Hints on](ootrando_overworldmap_hamsda/images/setting_hints_on.png "Hints on") Hintable locations will always show up on the map.

### Bean Planting

This setting determines how the Magic Beans will be handled on the map.

- ![Plant off](ootrando_overworldmap_hamsda/images/setting_plant_no.png "Plant off") The bean patches won't show up on the child map and adult locations will just show up once you have the bean item.
- ![Plant on](ootrando_overworldmap_hamsda/images/setting_plant_yes.png "Plant on") The bean patches will show up on the child map and adult locations require those to be checked off (meaning the bean has actually been planted there).

## Entrance Randomizer variants

The entrance randomizer variants are very different from the regular map tracker variants. The map does not include any item locations to be checked, because that would result in way too many spots on the map, but instead has locations for the randomized entrances. They all have a capture spot, where one can mark what is at that location. If the location is useless, just mark off the icon to clean up your map. Later you can see what led where by simply hovering over the locations.

There are two variants, one for keysanity and one without, but only a few of the items are actually used for "logic" (to show/hide some entrances).

The only setting to select is how many of the entrances are randomized ([see wiki](https://wiki.ootrandomizer.com/index.php?title=Entrance_Randomizer)):

- ![ER Dungeons](ootrando_overworldmap_hamsda/images/setting_entrance_dungeons.png "ER Dungeons") Only the dungeon entrances are shuffled with each other.
- ![ER Indoors](ootrando_overworldmap_hamsda/images/setting_entrance_indoors.png "ER Indoors") Indoor entrances like grottos and houses are shuffled as well.
- ![ER Overworld](ootrando_overworldmap_hamsda/images/setting_entrance_overworld.png "ER Overworld") In addition most overworld connections are shuffled.

Additionally there are counters for the useful indoors entrances, so you can evaluate how much focus to put on exploring more entrances:

- ![Counter: Generic Grottos](ootrando_overworldmap_hamsda/images/entrance_grotto_generic.png "Counter: Generic Grottos") 9 generic grottos (1 chest, 1 gossip stone).
- ![Counter: Scrubs](ootrando_overworldmap_hamsda/images/entrance_grotto_scrub.png "Counter: Scrubs") 10 grottos that contain 2 or 3 scrubs each. Only 2 of these are relevant if scrubsanity is off.
- ![Counter: Cows](ootrando_overworldmap_hamsda/images/entrance_grotto_cow.png "Counter: Cows") 4 grottos/houses that only have a cow (Impas House Back, Ingo Barn, Lon Lon Corner Tower, Mountain Bombable Grotto). The other cow spots have their own markers (![Links House](ootrando_overworldmap_hamsda/images/entrance_house_link.png) and ![Field Valley Grotto](ootrando_overworldmap_hamsda/images/entrance_grotto_field_valley.png))
- ![Counter: Great Fairies](ootrando_overworldmap_hamsda/images/entrance_house_fairy.png "Counter: Great Fairies") 6 Great Fairy Fountains.
- ![Counter: Shops](ootrando_overworldmap_hamsda/images/entrance_house_shop.png "Counter: Shops") 7 randomized shops (Kakariko Potion Shop is fixed).

I made a [quick explanation](https://www.twitch.tv/videos/429980574) on how to use the ER variant.
