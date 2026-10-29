# OpenZ change log

## OpenZ 1.2 (29 Oct 2026)

OpenZ is a free fan remake of the original Z (The Bitmap Brothers, 1996), the real-time strategy game where flags and territory decide the battle and time is the only resource. Version 1.2 lets you play the blue side, General EvilZod's faction, and brings a Unit editor, a new medium tank, new looks for five units, a computer opponent that flies shuttles and repairs its vehicles, new voice lines, many fixes and an experimental Linux version beside the Mac one.

**Downloads:** `OpenZ_1.2_win64_part1.zip`, `part2` and `part3` (Windows 10 / 11, 64-bit: unzip all three into the same folder), `OpenZ_1.2_mac_EXPERIMENTAL.tar.xz`, `OpenZ_1.2_linux_EXPERIMENTAL.tar.xz` (also for the Steam Deck) and the source code in two parts.

### New

- **The blue side**, a full faction of its own: General EvilZod of Evil Takeover Industries, as confident and strong as Zod, with his small, easily scared sidekick BS-01 (no mouth, big glowing eyes). Play all three maps from the blue fort while the computer plays red.
- **A faction screen** before every level: PLAY opens two recruiting posters, General Zod of ZodCorp for the red side and General EvilZod for the blue side. Point at a poster to read its general's dossier card; Zod has a word to say about your pick.
- EvilZod's own scenes in his comms window: a briefing over a fly-over of each map; when the red fort falls, his World-Domination-inator drops a blue nuke on it, then his victory scene; when your fort falls, his defeat scene. On the level selection he has his own lines for each map.
- **A new vehicle, the medium tank**: between the light and the heavy tank, built right after the mech in every fort and factory that builds the mech. A little tougher and slower than the mech, it fires the light tank's cannon with a hard turret kick, speeds up when it manoeuvres under fire and aims a little less surely until it becomes a veteran. The computer builds both, about one of each.
- **New looks** for the heavy tank, the light tank, the MLRS, the mech and the gun: the same size, weapons and behaviour, with their own pictures in the build menu. At night the new mech's blue eyes light the ground like a jeep's headlights. In the levels every unit uses its new look, and the testing mode (P) has a tile for the old and the new look of each.
- The mech's machine gun now fires at robots between its rocket salvos, and a badly damaged mech can lose it. For the extra gun the mech has 5 % less health, and the build menu calls it a "Mech with rockets and a machine gun."
- **Unit editor**, a new main menu section under PLAY: place the units of both teams on an empty field, add flags, an obstacle and grenade crates, and watch them fight on their own. Compare their stats in four sets (OpenZ, ZodEngine, Z-Wiki and your own Custom numbers), and save and load your setups.
- **Custom unit stats in the levels**: once you have saved Custom stats in the Unit editor, the UNIT STATS switch over DEPLOY (key N) plays any level with your numbers for both teams. Custom matches stay out of the high scores.
- The computer opponent uses shuttles now: it flies squads to flags nobody defends. It also sends its damaged heavy vehicles to its repair station and back, and guards its border flags.
- The shuttle shows who is inside and how many, on its card and over the ship.
- A wrench key pops up above R while a damaged vehicle is selected and you own a repair station: one click sends it for repairs and back.
- HIGH SCORES count the wins of both sides, and every row shows the general who won it, ZOD or EVILZOD.
- New voice lines: 15 repair lines for the vehicles, 10 for the mech, 22 for the medium tank, 10 more for the pyros, and "No way!" and friends when a lone robot is sent against something far stronger. As in the original Z, the announcer now also says "Radar activated." and "Your fort is under attack!", and a robot that takes an empty vehicle calls "Vehicle captured!".
- CHROMATIC ABERRATION in the graphics options (off by default): a soft lens fringe towards the edges of the screen.

### Changed

- Flags are easier to see: lamps and glows at night, coloured rings by day.
- Level 16, the Jungle, zoomed all the way out: the land now runs on beyond the map's edge with old ruins, groves, hills and swamps, and the camera no longer drifts far past the map's sides. The widest zoom there is a little closer.
- Snipers are a little weaker, and grunt and psycho rifles now hurt them. Jeeps now and then shoot the drivers out of light tanks, medium tanks and mechs too.
- FREE CAMERA is now on by default (OPTIONS, GAME): hold the middle mouse button to turn and tilt the view. If you had switched it off, it stays off.
- The closest zoom stays a view of the battle; with FREE CAMERA a low tilt pulls the camera back.
- The OPENZ DISCORD button in the main menu uses an invite that does not expire.
- Every tank, the MLRS, the mech and the gun now kick back on every shot and settle again, and the turrets and the MLRS's launcher turn smoothly between targets without shaking.
- Tracks follow the ground over slopes, bumps and bridge ramps and roll as the vehicle drives. The medium and heavy tanks' tracks are a dark military grey, and a standing tank's tracks stay still while you zoom.
- A destroyed gun falls apart at once, and wrecks stay where they lie while you look at them; they sink only once the camera has moved away.
- In the briefing fly-overs the robots are on the phone or drinking rocket fuel until you get control, and the fly-bys behind the main menu were filmed again with the new looks.
- Unit editor: a RESET STATS button, simple windows like a game's menus, room for 200 units a side, a right click that never moves the camera, and CLEAR FIELD also clears wrecks and debris.
- The blue side: EvilZod's HQ has a military base wall and a steel deck floor, his Car Park briefing's view from above turns slowly, the SHUTTLE switch (key U) works for blue too, and the Car Park has an empty shuttle on each side. Head start vehicles always park clear of the shuttles.
- Pictures: every vehicle and gun picture in the build menus has the same desert tan look and size, the empty units in the testing mode and the Unit editor share one clean grey look, and the shuttle's pictures are relit to match the others.

### Fixed

- The drivers of the crane and the APC can be shot when they come up to fire; the empty vehicle can then be captured.
- Shift orders add to what your units are already doing, and robots walking out of a vehicle can be selected at once.
- The hand-grab cursor over grenade crates, as in the original Z.
- Kill cheers and quips are heard again in big fights, and the "Boom!" cheer comes right after a big enemy vehicle or gun is destroyed.
- A destroyed MLRS's tracks fall apart, and a factory's build time shows at every zoom.
- No black screen when a level starts without its fly-over. Every fly-over shows the rising sun from its first picture, and with CALM MODE on a level no longer starts under a white layer.
- Repairs: vehicles sent with R reach every repair station, take turns on the pad and come back to where they stood.
- New vehicles leaving a fort or a factory no longer poke through the door, and the mech's standing feet no longer slide when it turns.
- Once the match is won or lost, units can no longer be selected or given orders, and the battlefield screen's comms card is gone as soon as the loading screen comes up.
- Playing the blue side, every vehicle and gun picture is in blue paint (also with YOUR TEAM COLOUR set to blue).
- The Jungle far out: no grey curtain over the land, the mist runs on to the horizon, the rain splashes land out there too, and the thick jungle beyond the map's rim stands on the ground again.
- The mech's broken move line is replaced, and the announcer's radar line fits: "Radar online." at the first radar, "Radar is back online." only after every radar was lost.
- The game no longer stops for half a second the first time a robot pulls out a phone or a drink.
- Looks: health bars are a very slightly darker green, empty light tanks look like the old empty light tank again, and the new MLRS has a closed hull between its tracks.
- Unit editor: dragging from the dock always picks the unit up, the grenade crate opens, pops and bursts as in the levels, field items answer with the click sound, and nobody calls out winning or losing.

### Experimental

- Touch screen and gamepad input (OPTIONS, ADVANCED tab, the TOUCH and GAMEPAD row).
- The Mac version.
- The Linux version.

CHANGES & UPDATES in the main menu lists every change, those of 1.1 and 1.0 included, and opens with the main additions of 1.2.

---

## OpenZ 1.1 (21 Oct 2026)

The first big update to the faithful open-source 3D fan remake of **Z** (The Bitmap Brothers, 1996). OpenZ 1.1 opens a third battlefield, **Level 16: Jungle**, where **Alan & Brad** finally join your army as a hero squad and their **shuttle** becomes the first unit in OpenZ that flies. On top of that: sniper headshots, jeeps that run robots over, high scores and army ranks, a smarter computer opponent and a long list of polish and fixes on every level. Free as always, never sold, 100% original assets.

In the game, the **CHANGES & UPDATES** screen of the main menu opens with the biggest additions under **NEW IN 1.1**, followed by every change OpenZ makes to the original game.

**Downloads:** `OpenZ_1.1_win64.zip` (Windows 10 / 11, 64-bit), `OpenZ_1.1_mac_EXPERIMENTAL.zip` (Mac, experimental) and the source code in parts (`OpenZ_1.1_source_part1.zip`, `part2`, ...: unpack all parts into the same folder).

---

### New

#### Level 16: Jungle

- A third battlefield: **Level 16, Jungle**. It sits between Desert and Car Park on the battlefield screen, which now shows three levels.
- Its own world: ruins and overgrown pyramids, huts, campfires and lamps, waterfalls, swaying rope bridges, a cracked old road and gravel paths from the factories and forts to the road.
- Jungle life: **crocodiles** wait in the deep swamp pools and take one robot from a squad that wades through, rolling him under or diving away with him. Robots near a hunting crocodile hurry to the bank, and their routes keep out of the swamp.
- Parrots, snakes and small animals that come out of the huts, and **monkeys** on the steps of the big temples that run off when danger comes near. Birds and monkeys leave at night and in the rain.
- Jungle weather: daytime rain with puddles on the paths and the low grass, wind in the plants, wet ground.
- Tall trees that stand in the way can be shot down, like rocks: they fall and leave a stump. Two overgrown pyramids can be destroyed.
- When a fort blows up in the jungle, the shock wave throws the trees around it and the birds flee.
- The wobbly rope bridges creak, knock and strain as units cross them, louder with heavier vehicles.
- Its own spoken briefing: Alan and Brad on their sun loungers, a sunrise flyover with birds crossing the sun, and a crocodile chase.
- Its own **WIN and LOSE endings**: Alan and Brad on their loungers watch a fort go up in a mushroom cloud, the enemy's when you win, their own when you lose.
- Two preview flybys, a sunrise battle and a night battle, on the Jungle card of the battlefield screen and in the main menu's background (the Desert always plays first).

#### The playable shuttle

- Alan and Brad's **shuttle** stands beside your fort on Level 16, in team colours, with lights and exhaust smoke. It is there on Easy and Medium; switching off the **SHUTTLE** box on the battlefield screen (on by default) leaves it out.
- It carries one squad straight over swamps, cliffs, forts and trees, then lands and lets them out at its back.
- Squads board and leave through an animated ramp at its back, like the troop carrier. Boarding, unloading and the door are quick, so it keeps up with real gameplay.
- You can order the squad out right at touchdown, even after a crash landing: they step out as soon as the shuttle has righted itself.
- A real flying machine: engine jets, a soft dust cloud under it, a gentle hover, smooth speeding up and slowing down with tilts in the turns, climbing over hills, forts and trees, trees bending under it and birds flying clear.
- Its legs fold flat under the belly in flight and come down again before it lands.
- Its shadow on the ground shows where it will come down, and turns red where it cannot land; Alan tells you when a spot is no good.
- Its route is drawn from the shuttle in the sky down to the goal. Hold **Shift** to give it several points: it flies the whole route and lands at the last one.
- Soft, springy landings with a landing mark and dust. Rough landings bounce, shake the camera and right themselves.
- Lights and searchlights at night.
- It smokes when damaged, and a clean landing on the repair station fixes it.
- Shot down in the air, it goes up in a big blast: it breaks apart into burning pieces, a handful of rocket fuel cans (Alan and Brad's favourite drink) fly out and clink down, and everyone aboard dies, their bodies thrown up and around before they fall with the wreck. Robots still on the ramp when it is destroyed on the ground survive.
- An easter egg: double right-click a far spot and the shuttle does a **kickflip** on the way, rolling forward through the air like a corkscrew, with ribbon trails and a long whoosh. It is a real corkscrew dash with a clear whoosh and the shuttle is harder to hit during it. On long flights under fire it now and then dodges like this by itself, with new quips.
- Landing spots are fair: the legs always stand on dry ground, and it never lands on a flag or a gun.
- Robots leaving it always finish their walk out before they fight or can be hit; their selection rings appear once they are really out.
- On **Level 17: Car Park**, an empty shuttle stands in the car park on every difficulty for you to take, and on Easy and Medium the SHUTTLE box parks one by your fort too. The computer does not fly shuttles yet.

#### Alan & Brad: hero squad

- On Level 16, **Alan & Brad join your army** as a hero squad of two. They start on their sun loungers by a campfire.
- Much tougher than Grunts: they hit far harder, shoot further and repair themselves by 20% of their health a minute, up to full (the unit panel shows SELF-REPAIR 20%/MIN). Alan carries 5 grenades.
- Their own icons and voice lines. They drink rocket fuel when no enemy is near.
- They only board vehicles or guns when you order it.

#### All levels

- **Sniper headshots:** a Sniper's hit on a robot on foot is a headshot 15% of the time and kills at once, even a Tough. The head pops off with its own sound, the body drops where it stood, and your sniper sometimes calls it out. Sniping drivers works as before.
- A kneeling or lying Sniper is a smaller target: rifles, lasers and guns hit him less often and blasts hurt him less.
- **Jeeps run robots over:** jeeps on both sides drive at Toughs, Lasers, Electrobots, Snipers and Alan & Brad to run them over instead of standing in a gunfight (Grunts, Psychos and Pyros only up close), then drive back to where they were. Your move orders always come first. A Laser or a hero often shoots the driver of a jeep charging at him, and a Tough stands his ground and fires at it, so it is a fair fight.
- **Pyros burn buildings:** hold **Ctrl** when you order the attack, and Pyros set buildings and bridges on fire (without Ctrl nothing changes).
- **High scores and ranks:** every battle ends with a score and one of 14 army ranks, from Private to General, shown in one line on the end screen; only a win makes you an officer. A **HIGH SCORES** button (key **T**) on the battlefield screen shows the ten best wins of each level and difficulty, with rank, score, time, kills, losses, units built and zones. Kept on your computer only.
- **Ready guns:** finished guns wait as small READY icons beside their building. Click one to place it, or drag it straight onto the map.
- A selected gun's range ring greys out the ground it cannot hit behind rocks, cliffs and buildings. Its dashed sector lines are drawn only round real blind spots, so a gun with clear ground all round (often the howitzer) shows no lines at all.
- A factory you capture that still runs its default production shows a gently pulsing "!" on its badge until you have set its production and its rally point; pointing at it tells you what is still to do, and clicking the badge opens its production.
- Neutral flags are marked now and then by a soft ring of light on the ground, so they are easier to find.
- Robot bodies thrown by a blast whoosh through the air and land with a metal thud.
- The laser robot's shot lights the ground at his feet with a short green flash.
- New radio calls in the commander's window, and new robot answers such as "Yes sir!" and "Affirmative"; the grunts say "Grunts reporting!" and "Unit ready!".
- A tip for slow computers: when the game runs slowly (never in the first two minutes), a one-time note suggests lighter graphics; clicking it pauses the game and opens the graphics settings.
- An OpenZ Discord link in the credits and under the bug-report button.
- The CHANGES & UPDATES screen has a new **NEW IN 1.1** part with the major additions.

---

### Changed

#### Units and combat

- A Tough's rocket shot looks heavier: the bazooka kicks back harder, his upper body rocks and his free arm swings with it, while his boots stay planted.
- A Tough holds his aim through a kill, then turns smoothly to the next target (no more twitching between targets).
- Toughs and Snipers no longer step aside from shells and grenades: they stand and fire. Other robots step aside less often.
- Grenades: the blast is drawn at its real size, reaches a little wider and does 15% more damage. A direct hit on a vehicle does full damage, a near miss a little less.
- The burning ground a Pyro leaves slowly hurts enemy units that stay in it (a little every second; never your own units).
- A unit that becomes a veteran gets back 15% of its health (never over full).
- Tank and mech drivers who come up through the hatch now fire their own weapon (a laser driver fires a laser); other drivers fire a rifle, like the crane driver. No driver comes up on a bridge or in a fort or factory door.
- The defender on a fort's roof is now a sniper: longer range, and he still throws grenades when he has no clear shot.
- Units ordered into the enemy fort run straight in through its door, without dodging or waiting for each other.
- Units walk or drive round a rock when the way round is short, instead of blasting it.
- Robots' feet stay planted on the ground while they walk.
- Robots under fire no longer leave a fight on their own to grab a flag (a flag you click is still taken).
- The shuttle has 20% more health.

#### Computer opponent

- The computer now and then gathers a strike group in front of its fort and sends it together at your biggest army (after 8 minutes of play; can be switched off in Options).
- It builds a wider mix of units: from minute 8 on also heavy tanks and missile launchers, and Toughs, Psychos and Snipers in turn instead of mostly Pyros.
- On **EASY**, its big decisions come about 30% slower.

#### Wrecks, explosions and effects

- Light and heavy tanks break into real broken pieces of their own charred paint, with torn tracks and a loose wheel.
- A destroyed fort roof cannon crashes down heavily with dust and a concrete thud and breaks into broken pieces of dark, scorched metal in its own paint. The fort then shows a wrecked, burnt mount instead of a bare platform.
- Big falling pieces (vehicle wrecks, blown-off turrets, thrown robots, building chunks) never end up inside rocks, guns or buildings; a wreck piece in a unit's way settles into the ground and fades as the unit reaches it.
- A big wreck or fort cannon that comes down on a tree knocks the tree over.
- Debris and vehicle parts that fall into water splash, make rings and a sound, and rest partly under the surface.
- The fires burning on wrecks and ruins each flicker in their own rhythm instead of all blinking together.
- Fort explosions: the shock wave runs over hills instead of into them, and the dust is a soft fog that fades in and out.
- Dead robots and their parts slowly fade to a paler, greyer team colour, so they are never mistaken for live units.
- The Car Park preview flyby in the main menu and on its battlefield card is new: the red side fights back with every vehicle round its fort, and the fort falls in the new explosion.

#### Interface and controls

- The in-game interface can be rearranged by dragging its panels; the layout is remembered.
- A new key (**U**) hides and shows the bottom interface panels during a game.
- With a build menu open, **R** sets the factory's rally point (R again cancels); otherwise R repairs as before. The CONTROLS list shows both.
- Build menus: a bigger close button, a wide green SET RALLY button with a map pin, and PLACE now sits right after the guns with the waiting gun's picture.
- While a build menu is open, the message popups at the top stay away.
- The green area where you may place a gun looks cleaner and calmer: soft cells that match the real gun spots, faint "+" marks, rounded corners and an edge that fades out beside trees; it lies smoothly on craters and slopes.
- Gun range rings look exactly like the units' range rings (the same dotted ring, only the size differs).
- Move-order waypoint dots are dimmer at night.
- The closest zoom is a little less close and the widest zoom a little less wide.
- Testing mode: hold the middle mouse button to turn and tilt the camera; the minimap shows the turned view.
- The interface scale starts at 100% on every screen. A scale saved by 1.0 is reset to 100% once; a scale you then choose in Options is kept.

#### Graphics and performance

- The MEDIUM and LOW graphics presets are lighter for weak computers; HIGH is unchanged.
- The frame counter (when switched on) also shows the processor and graphics time of each frame.

---

### Fixed

- Snipers walk up, stop and fire: no more walking back and forth, and a sniper lies down only where he will stay for the rest of the fight.
- Toughs walk up, stop and fire: no more walking back after a dodging target or creeping after every kill.
- The Electrobot stands and fires when an enemy is in range instead of dodging back and forth.
- Units zig-zag and swerve far less on the way to their destination.
- A unit following a slower one (for example a mech behind a slow tank) keeps its pace calmly instead of stopping and starting.
- When one member of a squad is left far behind, he becomes a squad of his own instead of stretching the selection frame across the whole screen.
- When a group passes a free flag or an empty vehicle, one robot (the closest) now always takes it.
- No more short stall when a very large group gets one order.
- Drivers can no longer be shot out of their vehicle on a bridge or in a fort or factory door, where the empty vehicle used to block the way.
- A new vehicle coming out of the factory door carries its driver and crew at the right size and place the whole way.
- The rounds of a fort's roof defender start from his rifle (they could start several metres above him).
- Robots killed by an explosion are thrown at the moment of the blast, not half a second later.
- Vehicles and guns explode the moment the shot that kills them hits (a missile salvo could destroy a tank more than a second late).
- Explosions dig craters on every level when deformable ground is on; a crater on a road shows broken paving.
- A broken fort cannon's pieces no longer rest inside each other.
- The forts' big cannon rides on heavy hydraulic rams under its head, seen when you look into the fort from low with the free camera.
- Vehicles shake far less near shores.
- Waypoint dots no longer sink into the ground.
- Drag-selecting over a fort or factory no longer opens its build menu.
- In testing mode, a dragged unit icon no longer stays stuck on the screen.
- The factory reminder's tip sits right under the "!" on the badge, and its ring no longer touches the word TECH.
- With NIGHT & RAIN switched off, every map stays in daylight with no rain or storm (the Car Park still had them), and at night the picture brightens to day smoothly over a few seconds instead of in a flash.
- On the LOW graphics preset, tree shadows fade out smoothly at the widest zoom instead of popping.
- On the battlefield screen, the commander names a level only after you click its card (not when the screen just opens or when you only point at a card).
- The news announcer at the start of Desert and Car Park starts a moment after the briefing window opens, so its opening jingle is no longer lost while the level loads.
- No load or unload pointer while the shuttle is in the air.
- Fire puffs on a burning shuttle sit on its hull.
- Missile cannons aim the right way round.
- The shuttle never shows its inside up close to the camera.
- Robots leaving a troop carrier always finish their walk out before they fight or can be hit.
- Zod's rocket-fuel win joke now has a can and two giggles.

---

### Options

New settings rows (default in brackets):

| Setting | Default | What it does |
|---|---|---|
| **FREE CAMERA** | OFF | ON = hold the middle mouse button to turn and tilt the camera; the controls list then names it. |
| **FRAME RATE LIMIT** | 60 | 30 or 60 frames a second. |
| **RESOLUTION** | your screen's own | A lower resolution for slower computers. |
| **ENEMY STRIKE GROUPS** | ON | OFF = the enemy sends single units only. |
| **FRIENDLY UNITS OVERLAP** | NO | YES = your own units may pass through each other, as in the original game (they still go round buildings and rocks). The computer's units do too, so one grenade or shell can hit a whole bunch of them. |
| **FAST UNITS PASS SLOW ONES** | OFF | ON = faster units overtake slower ones. |
| **TRACKPAD SCROLL** | ZOOM | MOVE MAP = a two-finger swipe moves the map, Ctrl / Cmd + scroll zooms. |
| **SHUTTLE ORDERS** | LANDABLE SPOTS ONLY | ANYWHERE = you may also send the shuttle where it cannot land; it then hovers there until you move it. |

Renamed rows:

- The weather setting is now called **NIGHT & RAIN**, with a short, plain tip.
- The two shake settings are now **CAMERA SHAKE ON EXPLOSIONS** and **CALM MODE · NO FLASHES OR BLINKING**.

---

### Experimental (provided as is)

- **Mac version** (`OpenZ_1.1_mac_EXPERIMENTAL.zip`): an Intel build, not signed. On the first start, right-click the game and choose **Open**; see `HOW_TO_START_ON_A_MAC.txt`.
- **Touch screen and gamepad** input. Not yet tried on real devices.
- **TRACKPAD SCROLL** (MOVE MAP) has not been tried on a real Mac trackpad.

Please tell us how these work for you.

---

### Known issues

- With 60 or more units in one order, not every unit sets off at the same moment.
- On a slow frame rate, two camera cuts in the briefing window can come a fraction of a second late.
- On the Jungle at night, the blind-spot marks on a gun's range ring are harder to read than by day.
- One piece of debris on the Desert can rest slightly off the water surface.
- The shuttle's feet can sink very slightly into the ground on landing, and its broken hull pieces vary a little in colour from one crash to the next.

---

### Found a bug? Got an idea?

Use the bug-report button in the game, or come and tell us in the OpenZ Discord. Every report gets read.

OpenZ is an unofficial fan project, not affiliated with or endorsed by Rebellion or The Bitmap Brothers. Code GPL-3.0, assets CC BY-NC-SA 4.0.

## OpenZ 1.0 (12 Oct 2026)

First release: Level 2 (Desert) and Level 17 (Car Park).

[Back to the main page](../README.md)
