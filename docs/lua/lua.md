# Lua Documentation

## How to install Lua mods
Lua scripts you make can be placed either the `mods` folder in the base directory, or in `<SAVE FILE LOCATION>/mods`. You can also drag and drop mods into the window to install them.

Save file locations vary by platform. Here is a list of them:

- Windows: `%appdata%/sm64coopdx`
- Linux: `~/.local/share/sm64coopdx`
- MacOS: `~/Library/Application Support/sm64coopdx`

## Tips
- When developing Lua mods, run the game from a console. Lua errors and logs will appear there, but only if the game is launched with the `--console` launch parameter.
- When a function requests a time parameter, it is almost if not always in frames.
- You can use the `print()` command when debugging. Your logs will show up in the console.
- You can create a folder within the mods folder containing multiple lua scripts as long as one script is called `main.lua`. Dynos actors can be placed inside this mod folder under `<your mod folder>/actors/`.

## Sections
- [Globals](globals.md)
- [Constants](constants.md)
- [Functions](functions.md)
- [Structs](structs.md)

### Guides
- [Setting up Visual Studio Code](guides/vs-code-setup.md)
- [Hooks](guides/hooks.md)
- [gMarioStates](guides/mario-state.md)
- [Behavior Object Lists](guides/object-lists.md)
- [Lighting Engine](guides/lighting-engine.md)
- [ModFS](guides/modfs.md)

## Important notes on player indices

Something important to realize is that the `localIndex` for each player is different (unfortunately).

So the order of `gMarioStates[]`, `gNetworkPlayers[]`, and `gPlayerSyncTable[]` is different for each player.

Luckily `gPlayerSyncTable[]` will automatically translate the player indices, so setting `gPlayerSyncTable[0].example = 1` will set it for the correct player for everyone.

The `globalIndex` of each player is consistent among everyone connected. So if you absolutely need to sort things in order you will have to grab it from `gNetworkPlayers[<LOCAL INDEX HERE>].globalIndex`.

All of this is a holdover from when there were only two players. It was a reasonable idea back then.

!!! info
    Want some examples mods to go off of? Head over to [here](https://github.com/coop-deluxe/sm64coopdx/tree/main/docs/lua/examples) to see a list of example mods!