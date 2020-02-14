# Pokémon Solid Red and Solid Blue

This is a hack for Pokemon Red and Blue which aims only to fix the myrid bugs in Generation 1 Pokemon, and nothing else.

This is fork of the [disassembly of Pokémon Red and Blue](https://github.com/pret/pokered).

It builds the following roms:

* Pokemon Red (UE) [S][!].gb  `md5: 3d45c1ee9abd5738df46d2bdda8b57dc`
* Pokemon Blue (UE) [S][!].gb `md5: 50927e843568814f7ed45ec4f944bd8b`

## Things fixed in this ROM
* (nothing yet)

## Things still to be fixed in this ROM
* (everything)
* The ability to skip going to the Rocket Hideout by using a PokeDoll or Teleporting away from ghostly Marowak (init wBattleResult  to 2 at start of battle).
* The ability to see a wild ghost without the Silph Scope via viewing the stats menu.
* The ability to run into glitch pokemon on Cinnebar Coast ([switch to 8,9](https://discordapp.com/channels/333356453928894466/333366468794122240/672666681906298920)).
* The safari timer flag not being saved, allowing the timer to go off outside the zone.
* The bug where leaving the safari zone building may cause a load into Glitch City if entered via timer expiration.
* Timer expiration during jumping (step counter should not be decremented mid-jump).
* Disallow switching moves with Select in battle when transformed (or prevent Cooltrainer glitch some other way).
* Disallow save game to be loaded when there are -1 items in bag (or prevent item underflow glitch some other way).
* Fix ability to control for a frame before forced movement (cycling road skip).

## Things that Won't be Fixed
* The behavior of the move Wrap.
