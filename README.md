# PWLMP_Modpack
This repository contains some client configuration for the Promised Worlds Luna Multiplayer server. This will be listed on CKAN with the mod list as dependencies, allowing users to download all of the required mods easily.

## Patches
This mod disables Parallax collision, since different collision settings can cause conflicts between users on a multiplayer server.

It also adds a configuration to BetterTimeWarp which sets the physics warp at 0.999 - this eliminates yellow time, where the game reduces the accuracy of physics calculations to attempt to compensate for lag. Yellow time has claimed several vessels and many Kerbals on our previous LMP server, so this should help users with that problem.
