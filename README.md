# Card Wars: Adventure Time — PS Vita Port

A native PS Vita port of *Card Wars: Adventure Time*. Originally released for iOS/Android and shut down along with its servers, this port was meant to get the PC Port running on Vita hardware for a bounty. 

Built with Unity 2017.4 (PSP2), based on the PC port of the decompiled game.

<img width="960" height="544" alt="2026-07-03-032940" src="https://github.com/user-attachments/assets/ea72ac49-2bb3-4322-9760-7fb5a0589401" />

- Runs fine on 444mhz/111mhz


## Features

- Game has been converted for the most part into single player. 
- Mouse controls have been reverted back to touch controls.

## Installation

No VPK is provided directly. Releases contain an xdelta patch that must be
applied to your own copy of the original game.
You need version 1.11.0 of CardWars for iOS 6.0 (CardWars 1.11.0 iOS IPA)

1. Open Delta Patcher
2. Original file: select the IPA
3. XDelta patch: select `CardWarsVita.xdelta`
4. Apply patch — the output is `CardWarsVita.vpk`
5. Copy the VPK to your Vita and install with VitaShell

Saves are stored in `ux0:/data/CardWars/`. They survive updates and reinstalls as they are separate from the app. 
