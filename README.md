Crystalized Bedrock/Geyser Resource Pack!

Contributers for the assets used in this pack can be found [here](https://github.com/Project-Crystalized/Java-RP).

# Bedrock-Specific Contributers
TotallyNoCallum - Main Developer

# How to use
This Resource Pack was intended to be used with [Geyser](https://geysermc.org/).<br>

To get started, make sure you've [set Geyser up on your server](https://geysermc.org/wiki/geyser/setup/) and confirm it works. <br>
Go into the `Crystalied Bedrock` folder, And zip everything (where `manifest.json` is) into a zip folder (7-zip recommended) then rename the zip to a `.mcpack` file.<br>
Put the `.mcpack` file in `plugins/geyser-<platform>/packs` on your server. <br>
Next, take the `custom_mappings` folder inside `geyser_assets` and replace it with the `custom_mappings` folder on your server (in `plugins/geyser-<platform>/packs`) <br>
Restart your server if its on, and hopefully it should work next time you join.<br>

Completely unrelated side note, I recommend using [Geyser Extras](https://modrinth.com/plugin/geyserextras) on your server as well as Geyser (and Floodgate). This Plugin can make Bedrock's 1.9 PVP much better, Add the sweeping attack for swords for Bedrock players, and downloads [GeyserOptionalPack](https://geysermc.org/wiki/other/geyseroptionalpack/) automatically.

# Note about testing newer packs
If you experience visual bugs or anything broken, Try loggin out of your server, on the Bedrock client going into `Settings > Storage > Cached Data` and deleting the crystalized pack from there, it will redownload and update when you rejoin. The reason why this happens is because I dont update the pack version in `manifest.json` often, so bedrock thinks an old version and the newer version are the same thing and it doesn't update it client-side. <br>
Also Try Restarting your server if you change any Geyser custom mappings, do not `/geyser reload`.