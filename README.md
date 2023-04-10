# Flasks for Torchlight II

This mod adds permanent (non-consumable) health and mana flasks that can be used indefinitely. They work exactly like potions but more expensive and rare.

Part of the [Torchlite II](https://steamcommunity.com/sharedfiles/filedetails/?id=2553012355) roguelite pack.

## Installing

**Steam workshop**: press the *subscribe* button in [the workshop page]() and enable the mod via the game launcher.

**Manual**: download the latest version of the mod file from [the GitHub release page](https://github.com/tukkek/torchlight2-flasks/releases) and place it on your Torchlight 2 mod folder. If you're unsure the exact folder location, use the *Open mods folder* button on the official Mod Launcher tool. If necessary, check [this video](https://www.youtube.com/watch?v=e5KeocjLUiA) for step-by-step instructions.

## Balance

A flask works in the exact same manner as the equivalent potion of the same tier. They are, however a hundred times more rare and expensive than normal potions. That is because having 100% uptime in health and mana recovery is extremely powerful. 

The hundred-factor is probably overkill in favor of caution as an initial value (as players can achieve virtually the same for less by buying ample potions from vendors) and suggestions are welcome in further tuning it.

Flasks can drop from any source that would drop potions (more specifically the unit types `POTION`, `HEALTHPOTION` and `MANAPOTION`, directly or indirectly) so even though they are rare you are almost guaranteed to find a couple flasks along the way. It is much easier (but not guaranteed) to find them from vendors but their price is quite high - this is intentional, both as a form of gold sink and chase item, as Torchlight II leveling can use both.

Vanilla mana potions are rarer than health potions but both types of flasks are equally rare so as not to make mana flasks even more rare than currently.

There are many issues with adding such an item, including engine limitations and assumptions and mod compatibility, which is extremely important. Other designs were considered, tested and dropped in favor of the current implementation which I think handles the functional and non-functional satisfactorily.
