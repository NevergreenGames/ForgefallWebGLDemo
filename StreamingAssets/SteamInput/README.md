# Steam Input Setup

This folder contains Forgefall's bundled Steam Input action manifest.

In Steamworks partner settings, set Steam Input Template to `Custom Configuration (Bundled with Game)` and use this relative path:

`Forgefall_Data/StreamingAssets/SteamInput/steam_input_manifest.vdf`

Unity places `StreamingAssets` under `<GameName>_Data/StreamingAssets` in desktop builds. If the executable name changes for the Steam depot, update the partner-site path to match the generated data folder.

After uploading a build, create and export official Steam Input layouts for Steam Deck, Xbox, PlayStation 4, PlayStation 5, Switch Pro, and Generic controllers, then add those exported configuration paths into the manifest's `configurations` block.
