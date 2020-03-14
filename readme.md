I was using some of Rainbeau's mods, so I decided to (try and) migrate them to 1.1. Preferably all of them, but that is already proven to be difficult.

Here you can see the progress.

**Advanced Bridges** – Done at https://github.com/firefoxpdm/Rainbeau-s-Advanced-Bridges/releases/latest

**Archipelagos** – Done at https://github.com/firefoxpdm/Rainbeau-s-Archipelagos/releases/latest

**Concrete** – Done* at https://github.com/firefoxpdm/Rainbeau-s-Concrete/releases/latest

**Editable Backstories and Names** – I am not going to migrate this mod. The categories have changed: not only names, but also which pawn types they are supposed to cover. I am not even sure I know all the currently existing ones as there doesn't seem to be an enum covering them. I am also sure that "Outlander, Offworld, Tribal, Pirate, and ImperialRoyal" are not all of the existing ones, because if they are then the base game is broken as it lists "Civil" as the sole category in the fallback backstory filter. Additionally, this pack doesn't contain any royal backstories, which means exclusive use of this mod's backstories (the default setting) with the Royalty mod would trigger errors and break immersion completely. As for the names part, they are far too tied together with the backstories and the extra filtering RF was trying to do with the backstories, so I'd rather not touch any of that.
What I *could* see happening is to create a mod for name and backstory handling in place of the original one, and then creating mods that add names and backstories based on this, but that would no longer be a rewrite of this mod, and it would require someone to create the missing backstories for the Royalty update.
Long story short, please check Kiame Vivacity's upgrade at https://steamcommunity.com/workshop/filedetails/?id=2020029291 if you still want to have this.

**Etched Stone Walls** – Done* at https://github.com/firefoxpdm/Rainbeau-s-Etched-Stone-Walls/releases/latest

**Fertile Fields** – Done* at https://github.com/firefoxpdm/Rainbeau-s-Fertile-Fields/releases/latest

**Fishing** – Done* at https://github.com/firefoxpdm/Rainbeau-s-Fishing/releases/latest

**Packed Lunches** – Done at https://github.com/firefoxpdm/Rainbeau-s-Packed-Lunches/releases/latest

**Pawns Are Capable!** – Done* at https://github.com/firefoxpdm/Rainbeau-s-Pawns-are-Capable/releases/latest

**Permafrost** – Done* at https://github.com/firefoxpdm/Rainbeau-s-Permafrost/releases/latest

**Rainbeau Flambe - Storyteller** – Done at https://github.com/firefoxpdm/Rainbeau-Flambe---Storyteller/releases/latest Some configurations has changed between 1.0 and 1.1, in these cases I tried to pick the settings that resembled the original ones the closest. Check the release notes for the technicalities.

**Rational Romance** – Done* at https://github.com/firefoxpdm/Rainbeau-s-Rational-Romance/

**Realistic Planets** – Done* at https://github.com/firefoxpdm/Rainbeau-s-Realistic-Planets/releases/latest

**Rim Disorders** – Done* at https://github.com/firefoxpdm/Rainbeau-s-Rim-Disorders/releases/latest

**Rumor Has It** –  Done* at https://github.com/firefoxpdm/Rainbeau-s-Rumor-Has-It/releases/latest

**Scenarios** – Done* at https://github.com/firefoxpdm/Rainbeau-s-Scenarios/releases/latest

**Tribal Pawn Names** – Done* at https://github.com/firefoxpdm/Rainbeau-s-Tribal-Pawn-Names/releases/latest

**Tribal Raiders** – A pre-release version is available at https://github.com/firefoxpdm/Rainbeau-s-Tribal-Raiders/releases/latest This mod contains new backstories for raiders, the handling of which has changed between 1.0 and 1.1. It has the same problems as the editable backstories and names mod. However, since here this feels just like an additional thing instead of the main functionality, I have decided to remove them (the backstories) to provide a first draft, and will revisit it once I figure out how they can be integrated into 1.1. You will also see error messages pop up along the lines of "No shuffled Childhood found for archer chief of TribalRaiders. Choosing random.". These should be safe to ignore.

**Wild Cultivation** – Done* at https://github.com/firefoxpdm/Rainbeau-s-Wild-Cultivation/releases/latest

If you find some issues with them, please open a ticket. Since I am not the creator, it is unlikely that I can provide any new features.

The entries marked with a * are waiting for a final code cleanup.
