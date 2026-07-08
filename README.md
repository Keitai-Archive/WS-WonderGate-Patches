# WS-WonderGate-Patches
Patches that help with enabling MobileWonderGate features in WonderSwan and WonderSwan Color games.

# WonderGate Menu Unlock
In the first set of MobileWonderGate compatible games released for WonderSwan, the WonderGate menu option was hidden behind a button combo that had to be held at boot. This button combo is hard to replicate in emulator, so these patches will enable the WonderGate features automatically without needing it. They apply to the following games:

- Buffers Evolution (BUFFERS EVOLUTION)
- D's Garage Koubo Game: Tane wo Maku Tori (D's Garage21公募ゲーム　たねをまく鳥)
- SD Gundam: Gashapon Senki Episode 1 (SDガンダム　ガシャポン戦記　－エピソード１－ )
- Sennou Millenium (線脳　MILLENNIUM)
- Tarepanda no Gunpey (たれぱんだのぐんぺい)

# Additional Patches
The following is a collection of miscellaneous patches related to MobileWonderGate features.

##Star Hearts: Hoshi to Daichi no Shisha (スターハーツ ～星と大地の使者～)
Star Hearts in its original form is unable to save when using the **mednafen** emulator because the cartridge header declares a 8KB save while the game actually uses a 32KB save. This patch edits the header so that mednafen correctly reads the game as a 32KB cartridge. This patch is not needed for other emulators such as Ares and Mesen2.


