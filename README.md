# Pokémon Solid Red and Solid Blue

This is a hack for Pokemon Red and Blue which aims only to fix the myrid bugs in Generation 1 Pokemon, and nothing else.

This is fork of the [disassembly of Pokémon Red and Blue](https://github.com/pret/pokered).

It builds the following roms:

* Pokemon Red (UE) [S][!].gb  `md5: 3d45c1ee9abd5738df46d2bdda8b57dc`
* Pokemon Blue (UE) [S][!].gb `md5: 50927e843568814f7ed45ec4f944bd8b`

## Things fixed in this ROM (if checked)
* [ ] Glitch Mons (Provide proper error handling pokemon for undefined/glitch mons).
* [ ] [Super Glitch](https://bulbapedia.bulbagarden.net/wiki/Super_Glitch_(move)) (provide proper redirect to a move like Splash as error handling).
* [ ] One-Frame Control Glitch (Fix ability to control for a frame before forced movement).
* [X] Old Man Glitch (The ability to run into glitch pokemon on Cinnebar Coast, [switch to 8,9](https://discordapp.com/channels/333356453928894466/333366468794122240/672666681906298920)).
* [ ] [Evolutionary stone bypass](https://bulbapedia.bulbagarden.net/wiki/List_of_glitches_in_Generation_I#Evolutionary_stone_bypassing)
* [ ] [Oak's pokeball delivery text overlap](https://bulbapedia.bulbagarden.net/wiki/List_of_glitches_in_Generation_I#Oak_Pok.C3.A9_Ball_delivery_text_overlapping)
* [ ] [Pewter Gym Skip](https://bulbapedia.bulbagarden.net/wiki/Pewter_Gym_skip_glitch)
* [ ] [Broken hidden items](https://bulbapedia.bulbagarden.net/wiki/Broken_hidden_items)
* [ ] Trainer Fly (ability to pause the frame before a trainer spots you).
* [ ] Ghost Marowak Bypass Glitch (The ability to use a PokeDoll or Teleport to win the ghostly Marowak fight, init wBattleResult  to 2 at start of battle).
* [ ] Ghost Identity Unveiling Glitch (The ability to see a wild ghost without the Silph Scope via viewing the stats menu.)
* [ ] Safari Zone Timer Glitch (The safari timer flag not being saved, allowing the timer to go off outside the zone.)
* [ ] Glitch City via Safari Zone (The bug where leaving the safari zone building may cause a load into Glitch City if entered via timer expiration.)
* [ ] [Glitch City](https://bulbapedia.bulbagarden.net/wiki/Glitch_City)
* [ ] Walk over Walls via Safari Zone (Timer expiration during jumping, step counter should not be decremented mid-jump).
* [ ] Cooltrainer Glitch (Disallow switching moves with Select in battle [when transformed](https://bulbapedia.bulbagarden.net/wiki/List_of_glitches_in_Generation_I#--), or prevent Cooltrainer glitch some other way).
* [ ] Ditto Assumption Glitch (Fix problem with transform being used by someone other than Ditto in wild leading to Ditto being caught.)
* [ ] [Item Underflow Glitch](https://bulbapedia.bulbagarden.net/wiki/Item_underflow) (Disallow save game to be loaded when there are -1 items in bag, or prevent item underflow glitch some other way).
* [ ] [HP Recovery Move Failure](https://bulbapedia.bulbagarden.net/wiki/List_of_glitches_in_Generation_I#HP_recovery_move_failure)
* [ ] [Levelling Past 100 oversight](https://bulbapedia.bulbagarden.net/wiki/List_of_glitches_in_Generation_I#Leveling_past_100)
* [ ] [Catch rate errors](https://bulbapedia.bulbagarden.net/wiki/List_of_glitches_in_Generation_I#Catch_rate_errors)
* [ ] [Division by 0 errors](https://bulbapedia.bulbagarden.net/wiki/List_of_glitches_in_Generation_I#Division_by_0)
* [ ] [Biking Reset Oversight](https://bulbapedia.bulbagarden.net/wiki/List_of_glitches_in_Generation_I#Save_reset_oversight)
* [ ] [Save-Surf Exploit](https://bulbapedia.bulbagarden.net/wiki/List_of_glitches_in_Generation_I#Save_Surf_exploit)
* [ ] ...anything else found [here](https://bulbapedia.bulbagarden.net/wiki/List_of_glitches_in_Generation_I).

## Things that Won't be Fixed
* The behavior of the move Wrap.
