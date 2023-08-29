# RoL Giants Mod

Really just my repository for whatever big stuff I can do in Rise of Legends. So far, this contains units that can only be accessed via scenario editor under Empty Nation Slot. I've noted every new section with the word "addon" in the XML files. I've also edited every unit to not deal damage to its trampler 'cause that's a silly mechanic.

Based on the DVD rerelease, in case that makes a difference.

## How to Set Up Mods?

These are the steps I took from scratch to make the game moddable.

- Ran ModPack.exe that came with the game to get basic mod XML files.

- Used ROL Big Archiver to extract the ``multiplayer_data.big`` in ``.\data\patch8`` (the patch8 folder has newer file dates than the used archives???).

- Copied its contents into the game's directory.

- Moved ``data.big`` and ``multiplayer_data.big`` out of the root data directory.

- Moved ``soundinfo.big`` out, as well, so audio.xml can be read from.

- That's all?
