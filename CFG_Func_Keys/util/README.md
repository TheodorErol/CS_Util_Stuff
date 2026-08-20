# CS2 Utility Practice Config

A simple CS2 practice setup for quickly learning and practicing utility lineups.

## What does it do?

This config sets up a dedicated practice environment with:

* Infinite grenades and ammo
* No money or buy restrictions
* No round/freeze-time limitations
* Grenade trajectories and impact markers
* Bots automatically removed
* Useful practice settings enabled

You can quickly load supported maps and practice different utility lineups using your **Function Keys F1**.

**Care, this means if you have anything bound on your Function keys this will remove it.**


## How to use it

Put the whole folder util into something like ../Steam/steamapps/common/Counter-Strike Global Offensive/game/csgo/cfg

You can find your folder via: Rightclick CS2 in Steam. Select Properties/Eigenschaften then go to Installierte Dateien and click Durchsuchen..

The ../Counter-Strike Global Offensive will open. From there go /game/csgo/cfg and put the util folder here.

Go into any Map via Play -> Practice -> Choose a Map and Disable Valve Map Guide.

**Start with "exec util/main".**

If you don't have noclip bound you can do **"bind p noclip"** and then use p to toggle noclip.

Once loaded, the **function keys control everything**.

* **F10** → Will always Clear/Reset the current selection and bring you back to select a map.

The console will always tell you what the current Function keys do.

## Important

If you get confused or want to reset your current utility selection, use **F10**.

The config is intended for **practice only** and requires a practice server with cheats enabled.

If you ever feel lost you can also star over with exec **util/main**

If you died somehow and can't rebuy util etc. just restart with exec **util/main**

## Currently known bugs

When first selecting a map guide and then a nade set it sometimes uses the wrong/old set even from another map. Just restart via exec **util/main**.

Sometimes you don't have infinite grenades. Just restart via exec **util/main**.