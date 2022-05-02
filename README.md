# Baba Is You - The MEGA MODPACK

<sub>~~(Yes I know a totally inspired name. I couldn't think of another name for this abomination)~~<sub>

This...... is a big one. A **BIG** modpack that merges several (curated) Baba Is You mods from various people into one GIANT (mostly working) MODPACK.

## But first, a (serious) disclaimer...
The Mega Modpack was done more for experimental reasons compared to [my main modpack](https://github.com/PlasmaFlare/plasma-baba-mods). As such, I am not as motivated to maintain the Mega Modpack when it comes to fixing all bugs and odd behaviors between mods. Therefore, expect there to be many bugs here and there. This is what you get when you try to combine code from different independent authors, without the luxury of coordinating between said authors like in an organized company.

When it comes to deciding which mods to merge, there will be several restrictions to prevent myself from being overwhelmed. Please note that if I didn't include your mod, it's **not** because I hate it. It's because adding more mods to this huge modpack can increase the risk for more bugs and add more tedium when maintaining the code. I have to be careful in choosing interesting mods that don't render the modpack too difficult to manage.

## Alright, serious time over! Where are the goods?!
### [Download the modpack in the Releases Section!](https://github.com/PlasmaFlare/baba-mega-modpack/releases)

**Compatable Baba version: 464/465 on PC**

The main version currently includes these mods:
- [Plasma's Modpack](https://github.com/PlasmaFlare/plasma-baba-mods) - By @Plasmaflare#5648 (me!)
- [Patashu's Modpack](https://github.com/Patashu/Baba-is-You-Pata-Redux-Mods) - By @Patashu#8123
- Persist (From the levelpack "Persistence") - By @Randomizer#0769
- Past - By @EvanEMV#9099
- Stringwords (STARTS/CONTAINS/ENDS) - By @Wrecking Games#8371
- Word Salad (ALIVE/VESSEL/VESSEL2) - By Huebird#3471

## How to install
1. This modpack only works when you install into a levelpack. Pick an existing levelpack or create a new levelpack in the baba editor. (From baba title: `Level Editor -> Edit Levelpacks -> Create a new levelpack`)
    - Note that when installing a mod into a levelpack, the mod will only take effect within the levelpack itself.
2. Close the game and navigate to `<Baba game directory>\Data\Worlds\<world folder>`
    - If you created a new levelpack, `<world folder>` will most likely be named something like `63World`. To determine which folder is your levelpack, look in each folder for a `world_data.txt` file. Inside it, look for whatever you named your levelpack under `[General]`.
3. Edit `world_data.txt` and add `mods=1` underneath the `[General]` section.
    - `mods` will not be seen if you haven't configured your levelpack to enable modding.
4. Copy both `Lua` and `Sprites` folder to the levelpack folder. This should add the contents of `Sprites` to the one in the levelpack folder and also create (or update) the `Lua` folder in the levelpack.
5. And thats it! You can start baba again and navigate to the levelpack and start playing around.


## Pending mods I'm looking to merge

### [Metatext Mod](https://github.com/EvanEMV/Baba-Is-You---Metatext-Mod) - By @EvanEMV#9099
As of 5/1/22, Hempuli expressed thoughts of implementing metatext officially. And he even worked on an initial prototype last Baba stream. It is unknown if he will follow through with this, since I suspect there might be a lot of refactoring involved. If Hempuli doesn't follow through, then I'll add the mod as normal. Otherwise, I'll have to see how the metatext mod responds after Hempuli implements metatext officially.