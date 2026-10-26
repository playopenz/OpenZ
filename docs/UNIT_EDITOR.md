[Back to the main page](../README.md)

# The Unit editor

> **Part of OpenZ from version 1.2.** OpenZ is an ongoing project, and this page grows with every update.

<p align="center">
  <a href="../media/unit_editor/unit_editor_1.jpg"><img src="../media/unit_editor/unit_editor_1.jpg" alt="The Unit editor: blue and red units fighting around two holographic obstacles, the BALANCE tab open on the right showing every unit's build time" width="100%"></a>
</p>
<p align="center"><i>The Unit editor with the BALANCE tab open.</i></p>

## What it is

The Unit editor is a **playground for every unit in OpenZ**. It opens an empty, flat battlefield (320 by 200 metres)
with no factories, no fort, no computer commander and no winning or losing. You drop robots, vehicles and guns of
**both teams** onto it, give orders to either side, and watch them fight. Units fight on their own exactly as they do in
the levels: they shoot at what comes into range. Nobody announces victory or defeat, because there is none.

On the right sits a **stats box** with every unit's numbers: build time, health, damage, range and the rest. You can
switch the whole field between four sets of numbers: **OpenZ** (the game's own), **[ZodEngine](https://sourceforge.net/projects/zod/)**, **[Z-Wiki](https://zzed.fandom.com/wiki/Z_%28video_game%29)** and your own
**Custom** set, which you can edit and see in action straight away.

## What it is for

- **Testing how units match up.** How many grunt squads does it take to stop a light tank? What does a sniper squad do
  against a row of jeeps? Put them down and find out.
- **Testing interactions.** Robots climbing into empty vehicles and guns, capturing a flag, picking up grenades,
  shooting around (or through) an obstacle.
- **Balance experiments.** Compare OpenZ's numbers with the [Zod Engine](https://sourceforge.net/projects/zod/)'s and the [Z fan wiki](https://zzed.fandom.com/wiki/Z_%28video_game%29)'s, change any value in the
  Custom set, and watch what it does to a fight.
- **Big battles just for fun.** Up to 200 units a side.
- **Sharing.** Save a setup to a file on your own computer and send it to friends, or post it for us if you found
  something interesting.

## How to open it

In the **main menu**, pick **UNIT EDITOR**, right under PLAY. A loading screen shows one of three battle pictures, then
the playground opens with an empty field and the hint *DRAG UNITS UP FROM THE DOCK*.

To leave, press **Esc** (when nothing else is open) or click **MAIN MENU** at the top right. See
[Leaving the editor](#leaving-the-editor).

## The screen

| Part | Where | What it holds |
|---|---|---|
| **Top bar** | Top | RESET STATS, SAVE, LOAD, SHARE, the **?** card (all keys and mouse buttons) and MAIN MENU |
| **Counts and the gear** | Top left | How many BLUE and RED units are on the field, and the gear that opens the backgrounds |
| **Battlefield** | Middle | The fight itself |
| **Stats box** | Right | Tabs **STATS** and **BALANCE**, the **TABLE** button, the four stats sets |
| **Play bar** | Bottom, above the dock | PLAY / PAUSE, x1 x2 x4, CLEAR FIELD, SAMPLE FIGHT, SOUND ON / OFF |
| **Dock** | Bottom | The team switch, x1 / x3 / x5, the tabs of units, the EXTRAS and PIN |
| **Zoom bar** | Bottom left | A scale ruler, the zoom in %, zoom out, fit, zoom in and the compass |

**H** hides every panel (the top bar stays) so you can watch the fight on a clean screen; press H again to bring them
back.

## The dock

The dock is one row at the bottom of the screen.

- **RED / BLUE / NEUTRAL**: the side your next units join. Keys **1** (blue), **2** (red) and **3** (neutral) do the same.
- **x1 / x3 / x5**: how many squads or vehicles one drop places. x3 puts three side by side across the view, x5 a row of
  three with two more in front.
- **ROBOTS | VEHICLES | GUNS | SPECIAL**: the tabs. ROBOTS holds grunt to Electrobot, VEHICLES jeep to crane, GUNS the
  gatling, gun, howitzer and missile cannon, and SPECIAL the hero squad **Alan & Brad** and the **shuttle**.
- **The tiles**: each shows the unit in its team's paint. A robot tile shows how many robots are in one squad. The
  small **i** in a corner opens the unit's card. Units that were not in the 1996 Z (the Electrobot, Alan & Brad and the
  shuttle) have an amber corner and say OPENZ ONLY on their cards.
- **EXTRAS**: the neutral **FLAG**, the holographic **OBSTACLE** and **GRENADES** (a grenade crate). These are always
  neutral.
- **PIN**: when pinned, the dock always stays. Unpinned, it slides away shortly after the mouse leaves it and comes back
  when the mouse reaches the bottom edge. **P** hides or shows the dock.

**NEUTRAL** places only vehicles and guns, and they stand **empty**, waiting for a robot to climb in. Robots, the heroes
and the shuttle are never neutral (robots are never neutral in Z), so their tiles are switched off while NEUTRAL is
picked.

## Placing units

There are two ways:

- **Drag** a tile from the dock onto the field and let go.
- **Click** a tile, then click the field. **Shift-click** keeps placing the same unit, click after click. A right-click,
  **Esc**, the **DONE** button or a click on the same tile stops.

While you place, a see-through preview of the units lies on the ground at their real size, with the weapon's range ring
(and its blast ring for explosive weapons) and a line such as *GRUNT x5 (15 robots)*. Where there is no room, the
preview says so, and a short message tells you when not everything could be placed. You can also drag a unit's picture
from the stats box or from a unit card onto the field.

Placing works while the fight is paused, so you can set up both sides first and then press PLAY.

**Removing:** pick units and press **Delete**, or use the **REMOVE** button in the stats box. A removed unit simply
disappears, with no explosion. **CLEAR FIELD** in the play bar removes everything at once: units, flags, obstacles and
grenade crates.

## Picking and giving orders (both teams)

Unlike in a level, you command **both** teams.

- **Click** a unit, red or blue: it is picked and its stats open on the right.
- **Shift-click**, or drag a box on the ground, to pick more, from both teams at once.
- **Right-click** with units picked: the ground = move there, an enemy = attack it, the flag = take it, an empty vehicle
  or gun = a robot climbs in.
- **Ctrl + right-click**: forced attack on any unit, an empty vehicle or gun, or the obstacle (the obstacle only with
  explosive weapons).
- **Right-click with nothing picked** picks the unit under the mouse and opens its stats.
- **Esc** unpicks.

You can pick red and blue units together. Right-click a blue unit, and the red units you picked attack it while the
blue ones move to it.

The unit under the mouse shows a small card with its picture, health and five headline stats (BUILD, HP, DMG, RANGE,
DPS), and which stats set it runs. The picked unit shows its weapon range ring on the ground, and its name label says
which set it runs, for example *LASER 1868 / 2027 HP · CUSTOM*.

## The neutral flag

The **FLAG** extra places the game's own capture flag, neutral. It works as in the levels: the first robot or vehicle
of another team that touches it takes it for its team (never the shuttle or a gun). It can be taken back, but after a
change it holds for one second before it can change again. Pick units and right-click the flag to send them all onto
it.

Use it to test capturing, and fighting over a capture. The stats box shows the flag's owner and how many times it was
taken, and a short message on screen tells you who took it from whom.

## The holographic obstacle

The **OBSTACLE** extra places a neutral holographic box, 6 by 6 metres and 3 metres tall, with 10,000 HP.

- **It blocks every shot of both teams.** A unit that has the box in its line of fire holds its fire and walks round to
  see past it.
- **It blocks paths.** Robots and vehicles walk round it.
- **Only explosives can destroy it** (Toughs, tanks, mechs, the MLRS, cannons): pick them, then **Ctrl + right-click**
  it. Their splash damage hurts it too.
- You can place several side by side, but never on units, on the flag or on top of each other.

Use it to test **lines of sight**: while a unit is picked, a faint dashed line with a small cross runs to every enemy in
its range that an obstacle hides.

## Grenade crates

The **GRENADES** extra places the game's own grenade crate. A robot that walks over it (or is sent onto it) picks it up,
its squad gets the crate's grenades and the crate is gone, as in the levels. Toughs and Electrobots never take grenades,
and neither does a squad that still has some. Shots and blasts can blow a crate up. CLEAR FIELD removes crates.

## Empty vehicles and guns

Vehicles and guns placed under **NEUTRAL** stand empty. A robot of either team that climbs in takes it for its own
team: pick robots and right-click the empty vehicle or gun. Ctrl + right-click attacks it instead. Pointing at an empty
one shows its health and the hint *A robot can climb in*.

## The stats box

The stats box on the right has two tabs, **STATS** and **BALANCE**, and the **TABLE** button. The **>** button (or the
key **I**) hides it; click the thin STATS rail at the right edge (or press I) to bring it back.

### STATS: the unit list

With nothing picked, STATS lists all 20 units, grouped as robots, vehicles, guns and transport, with **Build**, **HP**,
**Damage**, **Range** and **DPS** in the set in use and how many of each stand on the field. A value in colour differs
from OpenZ's own number. Click (or right-click) a row to open that unit's full stats.

### STATS: one unit

A click on a unit on the field, a row of the list, or a right-click on a dock tile opens the unit's own page:

- its picture (drag it onto the field to place more), name, kind and how many are on the field;
- for a unit on the field: its team and live health, and a **REMOVE** button;
- right under the name, what the unit is, with its strong and weak points, in the same words as the game's build menu;
- all **14 stats** in four columns, **OpenZ**, **ZodEngine**, **Z-Wiki** and **Custom**, plus **vs OpenZ** (the Custom
  value against OpenZ's, in %). Build time comes first. Point at any value for a short explanation, with the fan wiki's
  own words and the kind of difference where there is one;
- at the bottom, **Custom from OpenZ / ZodEngine / Z-Wiki** (copy that set's values into this unit's Custom values) and
  **Reset unit**.

A flag or an obstacle gets its own small page with what it does and its live state.

### The unit card

The **i** on a dock tile or a list row opens the **UNIT CARD**: a bigger card with the unit's picture, what it is, and
all 14 stats of the four sets side by side. The **<** and **>** buttons step through the units.

### BALANCE

The BALANCE tab (key **B**) shows **one stat for every unit** at once. Each unit gets four thin bars, one per set, all
on the same scale, the value of the set in use, and the biggest gap to another set when it is over 5 %. The arrows or
the **[** and **]** keys step to the previous or next stat, and the stat name opens a list of all 14. A click on a name
in the legend switches the field to that set. **Game order / High first** sorts the units, and **Linear / Log** changes
the bars' scale (log keeps small values visible).

### TABLE

**TABLE** (key **T**) opens one big sheet over the field: **every unit and every stat** of the set in use. You can
switch the set there too, show a small **+/- %** under every value against another set (**DELTAS VS**), and show only
the units on the field. Click a column head to sort high first, again for low first, again for game order. **CLOSE**,
T or Esc closes it. With Custom in use, you can edit the Custom values right in the sheet.

In the stats box, **--** means a source does not list that value and **n/a** that it does not apply to the unit.

## The stats sets

The four buttons under the tabs pick the set **the whole field uses**, every unit of both teams, at once. A unit keeps
its share of health when you switch: a unit at half health stays at half. The stats box always says which set is in use
here, and what the levels use.

| Set | What it is |
|---|---|
| **OpenZ** | This game, as played: the numbers the levels use, read from the game itself when the editor opens. |
| **ZodEngine** | The unit numbers of the open-source [Zod Engine](https://sourceforge.net/projects/zod/) (the Z remake whose gameplay rules OpenZ ports) for the 17 units of the original Z, without OpenZ's own rule changes. |
| **Z-Wiki** | The numbers the [fan wiki of the original 1996 Z](https://zzed.fandom.com/wiki/Z_%28video_game%29) lists. Some values are not listed there. |
| **Custom** | Your own values. They start as OpenZ's numbers, and you can change them. |

The Electrobot, Alan & Brad and the shuttle are not in the original Z, so ZodEngine and Z-Wiki do not have them. Under
those sets they run OpenZ's values, and their labels say so, for example *OPENZ (NOT IN Z-WIKI)*.

## Editing your Custom stats

In a unit's page (or in the BALANCE tab or the TABLE with Custom in use), the **Custom** values are boxes you can edit:

- click a box, type a number and press **Enter**; **Esc** goes back to the old value;
- the **mouse wheel** or the **arrow keys** change it in 1 % steps, with **Shift** in 10 % steps;
- a **right-click** puts that one value back.

**What a change reaches:** every unit of that kind on the field at once, both teams and empty ones too, and every one
you place later. A short message says so, for example *EVERY JEEP, BOTH TEAMS: CUSTOM HEALTH 2000 HP*. Two exceptions:

- **Squad** (robots per squad) counts for squads placed after the change. Squads already on the field keep their size.
- **Build time** only counts in the levels. Nothing is built in the Unit editor.

If another set was in use, your first Custom change switches the field to **Custom**, so you always see the change at
once.

Some values follow from the game's rules and cannot be typed in. They are shown, and pointing at them says which rule
fixes them. For example: Alan & Brad are two grunts, so their values follow the grunt's; guns do not move; the APC fires
the weapon of its crew; the crane's driver fires a grunt rifle. For the shuttle you can change its health and its
speed.

**Putting things back:** a right-click on one value, **Reset unit** for one unit, or **RESET STATS** in the top bar for
everything (see below).

### The 14 stats

| Stat | What it means |
|---|---|
| **Build time** | Base build time in seconds. Lower is faster. Only used in the levels. |
| **Squad** | Robots in one squad (1 to 8). |
| **Health** | Health of one robot or vehicle (HP). |
| **Damage** | Damage per hit. For explosives: at the centre of the blast. |
| **vs Grunt** | Damage per hit when the target is a grunt. |
| **Reload** | Seconds between shots. Lower is faster. |
| **Hit chance** | Chance to hit, in %. Shells and rockets have no hit roll: they fly to the spot they were aimed at. |
| **Range** | Weapon range in metres (one map tile is 2 m). |
| **Blast** | Blast radius in metres. 0 = it hits one target only. |
| **Shell speed** | How fast shells and rockets fly (m/s). |
| **Snipe** | The share of hits that go to the driver of an open vehicle or gun (%). |
| **Speed** | Move speed (m/s). |
| **Run time** | How long the unit can run at 1.8 times its speed (seconds). |
| **DPS** | Damage per second of one unit standing still: damage / reload x hit chance. Worked out from the others, not edited. |

## Playing your Custom stats in the levels

Your Custom stats **never change your normal games by themselves**. The levels play OpenZ's own numbers unless you
choose otherwise:

1. In the Unit editor, press **SAVE** (or **SAVE STATS AND GO** when you leave).
2. On the level screen a **UNIT STATS** switch appears over DEPLOY: **OPENZ** or **CUSTOM** (key **N**). It only appears
   once you have saved Custom stats that differ from OpenZ's.
3. Pick **CUSTOM** and deploy. Every unit of both teams, yours and the computer's, uses your saved numbers, build times
   included.

A **CUSTOM STATS** tag shows during such a match, and it does not go into the high-score table. **OPENZ** plays the game's
own numbers, exactly as before.

The editor also remembers your Custom edits between sessions before you save them, but only **saved** Custom stats can
be played in the levels.

## SAVE, LOAD, SHARE and RESET STATS

All of these are in the top bar.

- **SAVE** keeps your Custom stats as the ones the levels can play (see above) and writes a small file called
  `openz_custom_stats.json` in your **Documents** folder, under **OpenZ**, then **UnitEditor**. The file holds your
  Custom values and everything on the field: units with their health, flags with their owners, obstacles and grenade
  crates. SAVE always writes the same file name, so a new SAVE replaces the old file. To keep a setup, copy or rename
  the file.
- **LOAD** lists the stats files in that folder, newest first. **LOAD** takes a file's Custom values (the field switches
  to Custom). **LOAD WITH UNITS** also clears the field and builds it again with the file's units, flags, obstacles and
  crates. **OPEN FOLDER** opens the folder on your computer, so you can put a friend's file in it.
- **SHARE** saves the file and explains how to share it **yourself**. **OpenZ sends nothing anywhere:** no upload, no
  account, no internet needed. The window shows where the file is (**COPY PATH**, **OPEN FOLDER**). Send it to a friend
  in any chat, and they press LOAD in their own Unit editor. Want to show us? Post it on the OpenZ Discord: the
  **OPEN DISCORD** button opens the OpenZ channel of the ZZone Discord in your browser. A shared file changes nothing in
  anyone's game by itself: their levels only play it after they SAVE it and pick Custom on the level screen.
- **RESET STATS** asks first, then puts every Custom value back to OpenZ's own numbers, switches the field to OpenZ and
  removes your saved Custom stats, so the levels play OpenZ again. The file is not changed, so LOAD can bring its values
  back.

## Time controls

The play bar sits just above the dock.

- **PLAY / PAUSE** (or **Space**): stops or restarts the fight. While paused you can still place and remove units,
  pick them, edit stats and move the camera.
- **x1 / x2 / x4**: normal, twice and four times the speed.
- **CLEAR FIELD**: removes every unit, flag, obstacle and grenade crate at once.
- **SAMPLE FIGHT**: drops a small mixed fight on free ground, six groups a side (blue: grunts, psychos, a light tank, a
  gatling, snipers and a jeep; red: grunts, toughs, a mech, pyros, a howitzer and lasers). It never lands on units,
  flags or obstacles, and at most 6 sample fights can stand on the field at once.
- **SOUND ON / OFF**: mutes the battle (weapons, explosions, engines and the robots' voices) without touching your
  volume options. The music and the interface sounds stay.

## Camera

| Input | Action |
|---|---|
| Mouse wheel | Zoom in or out, towards the mouse pointer |
| Right drag | Move the view (a right drag gives no order) |
| W A S D / arrow keys | Scroll the view |
| Hold the middle mouse button and drag | Turn the view (left / right) and tilt it (up / down) |
| Compass (zoom bar) | Turn the view back to north |
| Home, or the fit button | Show all units on the field |
| Double-click on empty ground | Centre the view there |
| - / + buttons (zoom bar) | Zoom out / in |

The compass needle turns with the view and lights up while the view is turned or tilted. The ruler in the zoom bar shows
a true length on the ground. Note that in the Unit editor the **middle** button turns the camera and the **right** drag
moves it.

## Backgrounds

The **gear** at the top left, next to the unit counts, opens **BACKGROUND**: ten floor styles drawn by the game, switched
with one click. They are *Survey grid*, *Dot lattice*, *Micro-hex*, *Topographic*, *Range rings*, *Scan lines*,
*Triangle mesh*, *Blueprint*, *Tactical map* and *Carbon hatch*. Under **SHOW** you can turn on or off the floor lines,
a name label on every unit, and the floor's light motion. Your choice is remembered.

## Leaving the editor

**Esc** closes one thing at a time: a dialog, a card, the table, placing, the picked units, and so on. With nothing left
to close, it asks **GO TO THE MAIN MENU?** (the **MAIN MENU** button asks the same). The fight pauses while it asks,
and the first line says whether your Custom stats have unsaved changes.

| Button | What it does |
|---|---|
| **STAY** (Esc) | Back to the editor, exactly as before |
| **RESET STATS TO DEFAULT AND GO** | Every Custom value back to OpenZ's own numbers and your saved Custom stats removed (asks first) |
| **GO WITHOUT SAVING** | Drops the Custom changes since your last save (asks first if there are any) |
| **SAVE STATS AND GO** (Enter) | Saves your Custom stats and the file, then goes to the main menu |

## Keys

| Key | Action |
|---|---|
| Space | Play / pause |
| T | Table on / off |
| B | BALANCE tab on / off |
| I | Show / hide the stats box |
| P | Show / hide the dock |
| H | Hide / show all panels (the top bar stays) |
| Home | Fit: show all units |
| Delete | Remove the picked units (or the picked flag, obstacle, or empty vehicle or gun) |
| 1 / 2 / 3 | New units join blue / red / neutral |
| [ / ] | Previous / next stat in the BALANCE tab |
| Esc | Close the last thing open; with nothing open, GO TO THE MAIN MENU? |

These keys do nothing while you type a value in a Custom box. If you set one of them, in the controls options, to a
game action the playground also uses (such as stop, patrol, exit crew or scrolling), it keeps that game action. The **?**
button in the top bar shows all keys and mouse buttons in the game.

## Limits

To keep big fights playable, the field holds at most **200 units a side and 400 in all**. Every robot of a squad counts,
and so does every vehicle, gun and shuttle, empty ones too. The counts at the top left turn amber when a side gets close
to the limit, and a drop that does not fit says so (*RED IS FULL: 200 UNITS, THE EDITOR'S LIMIT*).

<p align="center">
  <a href="../media/unit_editor/unit_editor_2.jpg"><img src="../media/unit_editor/unit_editor_2.jpg" alt="A big battle in the Unit editor: a huge blue robot army charging a single red veteran missile launcher firing its rockets" width="100%"></a>
</p>
<p align="center"><i>A big battle: a blue army against a single veteran missile launcher.</i></p>

## Tips for balance testing

- **Pause first.** Set up both sides while paused, then press PLAY so both start at the same moment.
- **Keep it fair.** Use x3 or x5 so both sides get the same number of squads, and place them at the same distance.
- **Change one value at a time**, then run the same fight again. SAVE the setup and use **LOAD WITH UNITS** to build
  the same field again (positions and health included) for every try.
- **Compare before you change.** The BALANCE tab and the TABLE's **DELTAS VS** show where OpenZ, ZodEngine and Z-Wiki
  disagree, and by how much.
- **Speed up long fights** with x2 or x4, and pause to look at a moment closely.
- **Use obstacles for line-of-sight tests.** Pick a unit: the dashed lines with a cross show which enemies in range the
  obstacle hides.
- **Remember what does not show here.** Build time only matters in the levels, and squad size only for squads placed
  after the change.
- **Want to know why a number is what it is?** Point at it in the stats box for the fan wiki's own words and how OpenZ
  plays it.
- **Turn on "Name labels on every unit"** under the gear when a big fight gets hard to read.

## FAQ

**Does the Unit editor change my normal games?**
No. The levels always play OpenZ's own numbers, unless you SAVE Custom stats and then pick CUSTOM under UNIT STATS on
the level screen.

**Does OpenZ send my stats file anywhere?**
No. The file stays on your computer. Sharing it is up to you: send it yourself, in any chat or on Discord.

**How do I load a file a friend sent me?**
Put the file in the Unit editor's folder (click LOAD, then OPEN FOLDER to open it). Next time you open LOAD, the file is
in the list.

**Why can't I place a neutral robot?**
Robots are never neutral in Z. Only vehicles and guns can stand empty under NEUTRAL, waiting for a robot to climb in.

**Why do the Electrobot, Alan & Brad and the shuttle show OpenZ values under ZodEngine or Z-Wiki?**
They are not in the original Z, so those sets do not have them. They run OpenZ's values, and their labels say so.

**Why can't I edit some values?**
They follow from the game's rules (for example, guns do not move, and Alan & Brad follow the grunt's values). Point at
the value to see which rule fixes it.

**Who wins?**
Nobody. The Unit editor has no win or loss. The fight goes on until you stop it, clear the field or leave.

**How do I get back to the game's own numbers?**
RESET STATS in the top bar (it asks first), or Reset unit for one unit.

**Is there a computer opponent?**
No. There is no computer commander in the Unit editor. You give the orders to both sides, and units fight on their own
when enemies come into range.

[Back to the main page](../README.md)
