# Loconautics Changelog

## Ver 0.1.4BETA

### Bug Fixes
- Boiler parts can be targeted on their whole shape, not only the center.
- Railways boilers and smokeboxes now count as boiler bodies.
- Boiler lighting and shovel sounds play where the train is.
- A boiler with a steady water supply stays full, not a little short.
- The Creative Train Relocator no longer crashes the creative tab with a missing model.
- Scheduled steam trains no longer report no steam right after loading.
- Slow starts no longer play the wheel grinding sound.
- Safety valves stop blowing when their boiler is broken or gone.
- Steam Takeoff no longer darkens the blocks around it, untested.
- Pumps now pull water through a hose from an open pipe end.
- Pipes show moving fluid when a hose carries it.
- Raised smokestacks no longer turn black next to full blocks.
- Boiler bodies keep one even color next to other blocks.
- Lava buckets burned in a firebox leave their empty bucket.
- Boiler whistles stop blowing when their boiler is broken.
- Boiler parts on a train can be targeted on their whole shape.
- Carts no longer keep old roll, coupler and rerail state after a relocate or rerail.
- Copycat items no longer drop on the ground when a train crosses a portal.
- ISSUE 197: Bearing axle bogeys no longer crash the game when their model is not ready.
- Trains no longer jump or stall when they run off the end of a track.
- Unloaded trains stop at a dead end instead of running off it when loaded.
- Chat now says a car could not grip its track instead of no track.
- Parts on top of an upright boiler no longer float 8 pixels up.
- Cars no longer sway on their own over rail seams and junctions.
- Cars lean outward in curves and keep every wheel on the rail.
- Steady pushes no longer float a car above the rail.
- Bogey wheels no longer pull a leaning car back and forth.
- Bogeys roll with the car in both driving directions.
- Bogeys level out when the car stops leaning, with no sudden step.
- A rake that fails a portal crossing returns every car home, still coupled.
- Tanks, vaults and belts on a car keep their contents after a portal crossing.
- A rope with no holder drops as an item when a car crosses a portal.
- A rope to a body left behind is cut and dropped when a car crosses a portal.
- A car that cannot load after a portal crossing no longer leaves a ghost train behind.
- A rake with an unloaded coupled car is refused at a portal, not split.
- Long trains no longer slow the server down.
- A train saved while moving no longer jumps to another spot when the world loads.
- A train whose track was removed comes back off the rails on reload, not lost.
- Unloaded trains keep their car gaps after a reload and announce a departure once.
- A train that half leaves view parks as a whole instead of pulling cars with no body.
- Track observers see unloaded trains pass, unless the observer has a filter.
- Knuckles lock when a panel switch bound to them is turned on.
- Derailed cars no longer hang in the air when pushed or dragged while rerailing.
- Editing track near a train no longer resets its speed or makes it miss its station.
- A car with one loose bogey no longer fully derails when the track under that bogey breaks.
- Lopsided cars stop retrying the rerail after two quick roll offs, even after nearby track edits.
- Rerailed cars turn into place over a second instead of snapping the last few degrees.
- Derailed cars no longer rerail with one bogey left off the track.
- Chat says a car left a portal with no track instead of a raw text key.
- A strong plunger pull can lift a car off the rail again.
- A bogey that slips off later no longer loses its pull as if it ran off a track end.
- Cars lifted off the rail keep the speed they had instead of nearly stopping.
- The Physics Staff no longer throws cars off the rail with external force derail off.
- With curve derail off, cars no longer roll off the rail in curves.
- Cars drop off a track end right away instead of floating past it first.
- Breaking the track under a moving car drops it at once instead of two seconds later.
- A derail plays one crash, and the heavy thud waits until the car hits the ground.
- Chat says a car lost its bogeys instead of claiming the track is missing.
- The coupling stress warning reaches the driver when one bogey is pulled off.
- Cars thrown off with the physics staff keep rerailing instead of being called too lopsided.
- Derailed carts no longer twitch on the spot when only one bogey can reach the rail.
- Winch hoses no longer jump or lag behind the nozzle on a moving train.
- Hoses and steel cables no longer show up in another dimension.
- Hose Winches keep working after a reload, no need to break and place them back.
- Hose Nozzles no longer get flung away when hooked to a Hose Winch.
- Hose Nozzles turn freely again, the hose no longer fights the nozzle it is hooked to.
- A bogey placed on a physics body turns it into a train right away, untested.
- A train made from a placed bogey no longer jerks around on its first rerail, untested.
- Cars with long wheel plates no longer flip over right after they rerail.
- Derailed Railways cars only rerail onto track their bogeys can run on, untested.
- Bogeys no longer bounce when a car drops onto the track.
- Loose bogeys follow their wheel plate smoothly instead of skipping some ticks.
- Hose and steel cable length configs apply to winch ropes.
- Rollers on Sable trains break blocks in tunnel mode without a paving block.
- Analog controller speed limit moves one bar segment per scroll, like Create.
- Breaking a train block through a portal needs the right tool and drops its items at you.
- Coupled cars no longer shove each other apart while crossing a portal, untested.
- Trains wait at a portal until the far side has loaded, untested.
- Trackless cars coupled into a train cross portals with it, untested.
- Bogeys still behind a portal keep turning after the train crosses, untested.
- Holding Space while standing still approaches the station again.
- With two analog controllers in a car, the one being driven from is used, not whichever is found first.
- Cars behind the driver follow its steering, a car with its axle turned around no longer turns the other way.

- Deployers lay track along the car on a turned train.
### Added
- Boilers show a level in the goggles, set by their size and fire.
- Fuel quality sets the boiler fire limit, wood is weakest and coal blocks strongest.
- Redstone signal sets the boiler burn, 0 is full and 15 banks the fire.
- Boiler goggles show the power in use out of the total.
- Sneak on a working boiler to blow the train whistle.
- Steam whistles can sit on boiler bodies, firebox bodies and Steam n Rails boilers.
- Whistles sit on the round boiler, extensions included.
- Whistles on a boiler blow with redstone once it has pressure.
- Whistle sound and steam get stronger with boiler pressure.
- Panel parts can power any Redstone block listed in a datapack.
- Boiler Bogey drives steam trains from the analog controller.
- A shovel on a lit firebox door puts the fire out.
- Panel parts control the boiler burn, 0 burns full and 15 idles.
- Panel gauges can show how strong the boiler fire burns.
- A powered smart safety valve opens fully and blows off the pressure.
- Analog controller autofill reads the frequencies of the Boiler Bogey.
- Shift right click copies frequencies between the controller and the Boiler Bogey.
- Schedules run on trains driven by a Boiler Bogey.
- The firebox crackles like a blaze burner, and the sound follows its state.
- Schedules get a boiler fire entry that sets the burn.
- Fumes pile up in a firebox with no smokestack and burst out when the door opens.
- Flames burn inside the firebox and sparks fly out of the open door.
- Unloaded steam trains on a schedule stop when the fuel runs out, the owner gets told.
- Datapacks can set the fuel grade of any item.
- Lava buckets, blaze rods and blaze powder light the boiler.
- A config option scales how fast boilers burn fuel.
- Cold boilers lose their heat while the train is unloaded.
- Gauges can show the boiler level and the bogey power.
- The Boiler Bogey crafts from a Redstone Link, Boiler Tubes and Industrial Iron.
- A driving Boiler Bogey eases pressure down to 70 percent, keeping the valve shut.
- Railways smokeboxes hold water in a boiler, untested.
- A boiler that overpressures gives the Too Much Pressure advancement.
- Smokestacks show a placement ghost when you click a smokestack or boiler host.
- Hold Alt over a boiler body or firebox to see its water capacity.
- Single bogey cars lift their wheels on one side like other cars.
- The /loconautics lost command lists trains whose body went missing and can find them again.
- Grabbed objects keep the angle you turned them to and turn with your view.
- Holding something shows which key rotates it, like Create's hints.
- Datapacks can add engine fuels, with RPM and burn time per fluid.
- Sneak placing a Firebox raises it, and parts on it rise too.
- Smokestack column height is a server config, default 6 blocks.
- Panel gauges can read industrial tank contents and fill.

### Changed
- Steam takeoff power follows the boiler level, 16384 SU per level.
- Boilers need flint and steel or a fire charge to light.
- Boiler failures only put the fire out, nothing explodes.
- Fireboxes join in a straight line of three, a fourth starts its own.
- Bigger boilers take longer to warm up.
- Fireboxes have the round boiler hitbox and stack by clicking an end.
- Fireboxes use the round boiler shape with the inside showing.
- Boiler bodies join a firebox at its back.
- Boiler parts like the smokestack and valve work on any side.
- The firebox is now the Firebox Body and shows its shell as an item.
- Smokestacks sit raised on a boiler, firebox body or Steam n Rails boiler.
- Boiler whistles stay quiet until pressure reaches 30 percent of burst.
- Boilers burn more fuel and lose pressure the more power is used.
- Boilers keep steam after the fire goes out and cool down slowly.
- Steam takeoff speed and power are always whole even numbers.
- The safety valve hisses in one steady sound, not chuffs.
- A venting boiler burns through its water and can run dry.
- Burns for shows the shorter of the fuel time and the water time.
- Boiler bogeys pull less when the steam pressure is low.
- Boiler goggles show level bars like Create, on any boiler body.
- Boiler goggles tell you to light the fire and add an output.
- The steam release when a train stops comes from the Boiler Bogey.
- The safety valve hiss is quiet below half open and louder when fully open.
- Parts on a Railways smokebox sit flush, round bodies lift them.
- The analog controller arrow points at the axle front and turns with your camera.
- The boiler bogey item icon shows the real bogey with its wheels.
- The firebox item icon shows the shell, core and door.
- The train wheel item icon sits centered in the slot.
- Unloaded trains now move and keep their car gaps the way Create trains do.
- Unloaded trains load back in once their track is in a ticking chunk (Create parity).
- Boiler bodies have new end caps and a reworked shell.
- Boilers count 3 fireboxes and 9 body blocks, extra ones are decorative.
- Boilers use more water when the bogeys draw more of the pool.
- Boiler Bogeys pull harder and draw more steam for each wheel pair after the first.
- Bound panel parts glint and name their block, shift right click unbinds them.
- Rope and Physics Staff lift limits are configs again, the staff one can be 0.
- A slow car stops at a track end like a Create train instead of running off.
- The lever hold bar is wider and takes the part colors.
- Shovel right click takes one fuel, sneaking takes it all in full stacks.
- Firebox explosion on impact, along with its crash config options.

### Ponder
#### Instrument Panel
- Added a scene for connecting panel parts to blocks.

## Ver 0.1.3BETA

### Bug Fixes
- Nozzle sockets no longer break when water flows over them.
- Panel parts keep their links when a panel is copied with a schematic.
- The diagonal ribs on boiler bodies no longer show mirrored.
- Hose Connectors no longer hold two Hoses.
- The scroll picker opens when you tap its key fast.
- Copycat headstocks show the full texture border at every height.
- Hose connectors on a pipe now fill the tanks at the end of that pipe.
- Stickers on one train car no longer crash the game.
- The game no longer crashes on load with Dye Depot installed.
- Hose knots at nozzles and connectors now match the winch hose.
- Rope connector hoses no longer show a second knot stacked at the end.
- The winch hose flow animation runs toward the winch when pulling fluid in.
- Creative tab section banners no longer vanish when Bits n Bobs is installed.
- Schematics keep the copied block on buffers, knuckles and headstocks.
- Hoses between two trains stretch without pulling either car.

### Added
- Boiler bodies come in five red styles.
- Buffer colors and the knuckle or screw link pick from the scroll menu.
- Boiler bodies come in four metal colors from Create.
- Tubes, iron sheets and a fluid tank craft a boiler body.
- Any dye or a metal ingot recolors a boiler body.
- Nozzle handlebars fold in partway while a Hose holds the nozzle.
- Held blocks with a scroll picker show their key above the name.
- Copycat headstocks, knuckles and buffers connect textures with each other.
- Pick block on a copycat gives the copycat, sneaking gives its block.

### Changed
- Hose nozzles have a new model, and hoses end in a new knot there.
- Bound panel controls show the name of their block on the hotbar.
- Hose knots, strands and the winch reel have new textures.
- Ropes and hoses end in a knot at connectors.
- Nozzle sockets place their lid hinge on the side you aim at.
- A wrench turns nozzle sockets around the face you click.
- Valves craft 8 at a time, with the rod in the middle.
- All panel parts craft 8 at a time.
- The gauge needs a reinforced iron sheet and the button takes any button.
- Copycat headstocks come from zinc ingots at a stonecutter, 4 each.
- The knuckle and screw link take a copycat headstock in place of a panel.
- The creative tab shows the red ribbed boiler body.
- Colors follow one order from white to pink in the tab and pickers.
- Hose nozzle handlebars fold in when the nozzle docks.
- Item icons for the knuckle, buffer and nozzle sit centered.
- The boiler body is now the Industrial color on every kind.
- Boiler bodies list by color then kind in creative search.
- Knuckles and screw links craft 2 at a time.
- Industrial recipes take Create fluid pipes.
- Nozzle sockets craft 2 at a time.
- The casing and bogey picker key is V by default, not C.
- Copycat headstocks, knuckles and buffers take the sound of their block.
- The copycat headstock joins the knuckle in the coupler scroll menu.
- The mod needs Sable 2.0.5 or newer to load.

### Removed
- The red dye recipes for the analog controller, dashboard and conductors hat.

### Ponder
#### Hose Winch
- Changed all hose scenes, rebuilt from scratch.
- Changed the reeling scene to show the hose paid out and hauled in.
- Added a scene for letting the winch spin free.
- Changed the running a hose scene to show the line preview.
#### Hose Connector
- Added a scene for linking Fluids and one for Rope Connectors.
- Added a scene for linking fluids with connectors.
- Added a scene for extending hoses with rope connectors.
- Changed the rope connector scene to show a long run of connectors.
- Added a scene for how far a pump pushes Fluids.
#### Nozzle Socket
- Added a scene for docking nozzles.
- Changed the docking scene to show sockets with and without a tank.
- Added a scene for watering boilers through a socket.
#### Hose Nozzle
- Changed the nozzle scene to show holding and docking it.
- Removed the spraying scene.
#### Hose
- Changed the pumping scene to run through the new winch setup.

## Ver 0.1.2BETA

### Bug Fixes
- Bearing Axles above or below a bogey no longer drive it.
- Bearing Axles on the side of a bogey no longer drive it or turn it gray.
- The Analog Controller lever and speed bar now move outside trains.
- The Analog Controller lock keeps the current level.
- Leaving the Analog Controller lets its power decay instead of dropping to 0.
- The Hose Winch never gives more than 256 SU, at any speed.
- Dedicated servers let you place blocks again, right clicks no longer throw errors.
- The frequency trash button clears every frequency when you close the screen.
- Connecting a winch hose uses up the hose item in survival.
- Mekanism and other mods load again, the broken dye tags are gone.
- The game starts alongside the Destroy fork instead of crashing on load.
- Panels on moving trains show up and animate again.
- Valve gauges linked to an engine no longer crash the game without Propulsion installed.
- Joining a server with cables or hoses in view no longer crashes the client.
- Copycat blocks keep their item when a train crosses a portal.
- Analog controllers, bearing axles and transmissions keep their frequencies in schematics.
- Trains driven from a cab facing against the track reach full speed again.
- The world no longer crashes when a transmission loops back on itself.

### Added
- Transmission can be crafted from an analog transmission, redstone link and iron block.
- Bearing Axle can be crafted from a gearshift, redstone link and iron block.
- Gauge Lever sets Transmission speed and Gauge Switch sets its direction, bind with sneak click.
- Levers can be placed on the Transmission sides.
- Kinetic blocks show their stress impact or capacity in the item tooltip.
- Russian translation for the mod.
- German translation for the mod.
- Conductor hats change color with the scroll picker.
- Conductor's Goggles come in all 16 colors and show Create goggle info.

### Changed
- The Transmission and Bearing Axle menus only open with empty hands.
- Analog Controllers raise their output one level at a time and step back down.
- Analog Controller levels rise and fall slower.
- The Turntable Bearing trigger is a scroll panel on the block now.
- Spanish translation covers far more of the mod.
- Shears cut hoses but no longer cut steel cable.
- Nozzle spray wastes a quarter of the fluid it used to.
- Hose nozzles only grab when both of your hands are empty.
- Wrenches remove cables and hoses on a crouch right click.
- The train relocator moves trains out of portals and across dimensions.

### Removed
- The 16 colored hand brakes, the plain Handbrake stays.

### Ponder
#### Transmission
- Added five scenes for speed, direction and frequencies.
#### Bearing Axle
- Added five scenes on building and assembling a locomotive.
- Changed the assembly scene to show Sable train assembly and parking.
- Added a scene that shows how the axle marks the front.
#### Analog Controller
- Added two scenes on driving it and binding its frequencies.
#### Turntable Bearing
- Added eight scenes for the bearing, from assembly to parking and maneuvers.
#### Train Casing
- Added a scene for picking, placing and assembling bogeys into a train.
#### Bogey
- Added a scene for fitting a shaft through a bogey.
#### Dashboard
- Added a scene for the Dashboard.
#### Instrument Panel
- Added scenes for the part Interface and part looks.
- Added a scene for the Glass case.
- Changed the parts and controls scenes to show each click with its item.
