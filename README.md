# Card Wars: Adventure Time — PS Vita Port

A native PS Vita port of *Card Wars: Adventure Time*. Originally released for iOS/Android and shut down along with its servers, this port was meant to get the PC Port running on Vita hardware for a bounty. 

Built with Unity 2017.4 (PSP2), based on the PC port of the decompiled game.

<img width="960" height="544" alt="2026-07-03-032940" src="https://github.com/user-attachments/assets/ea72ac49-2bb3-4322-9760-7fb5a0589401" />

- Runs fine on 444mhz/166mhz `CPU/GPU` clock

## Installation

No VPK is provided directly. Release contain an xdelta patch that must be
applied to your own copy of the original game.
You need version 1.11.0 of CardWars for iOS 6.0 (CardWars 1.11.0 iOS IPA) (MUST BE ORIGINAL GAME FILES)

1. Install `CardWars_Stub.vpk` on your Vita with VitaShell
2. Download [xdelta3](https://github.com/jmacd/xdelta) ([Windows builds here](https://github.com/jmacd/xdelta-gpl/releases)) and put `xdelta3.exe`, the IPA and `CardWarsData.xdelta` in the same folder
3. Open a command prompt in that folder and run:     

`xdelta3 -d -B 536870912 -s Card_Wars_1.11.0_ios_6.0.ipa CardWarsData.xdelta CardWarsData.zip`

4. Extract `CardWarsData.zip` and copy its contents into `ux0:app/CWRS00001/`
and merge with the existing files
5. Launch Card Wars



Saves are stored in `ux0:/data/CardWars/`. Saves survive updates and reinstalls as they are separate from the game's actual data files. 
