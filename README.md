# WS-WonderGate-Patches
Patches that help with enabling MobileWonderGate features in WonderSwan and WonderSwan Color games.

# WonderGate Menu Unlock
In the first set of MobileWonderGate compatible games released for WonderSwan, the WonderGate menu option was hidden behind a button combo. Most games required the button combo upon boot, which is hard to replicate in emulator. 
One game requires a button sequence on a specific menu screen, which can be difficult to memorize. The patch for this game is an optional quality of life improvement. 

## Boot Combo Patches

| Game |  Original Boot Combo  | Notes |
| --- | --- | --- |
| Buffers Evolution (BUFFERS EVOLUTION)   | A+B+X2+Power ON | You need to complete at least one level in order to view any additional menu options besides **Enduro** |
| D's Garage Koubo Game: Tane wo Maku Tori (D's Garage21公募ゲーム　たねをまく鳥)   | X1+Y3+Power ON |  |
| SD Gundam: Gashapon Senki Episode 1 (SDガンダム　ガシャポン戦記　－エピソード１－ )   | A+B+Y3+Y4+Power ON |  |
| Sennou Millenium (線脳　MILLENNIUM)   | A+B+Y1+Y4+Power ON |  |
| Tarepanda no Gunpey (たれぱんだのぐんぺい)   | A+B+Y1+Y4+Power ON |  |

## Key Combo Patches

| Game |  Original Key Combo  | Notes |
| --- | --- | --- |
| Final Lap 2000 (FINALLAP 2000) | In ranking mode, press Y1/Y3/Y4/Y2 in that order | | 

# Additional Patches
The following is a collection of miscellaneous patches related to MobileWonderGate features.

## Star Hearts: Hoshi to Daichi no Shisha (スターハーツ ～星と大地の使者～) - Save Patch
Star Hearts in its original form is unable to save when using the **mednafen** emulator because the cartridge header declares a 8KB save while the game actually uses a 32KB save. This patch edits the header so that mednafen correctly reads the game as a 32KB cartridge. This patch is not needed for other emulators such as Ares and Mesen2.


