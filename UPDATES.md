All updaztes to enhanced are the same as legacy, unless they are exclusive to enhanced.
# Version 11.1.7 (Legacy)
# Version 1.5 (Enhanced)
- Added Vehicle > Spawner > Spawn At: Current Position or Closest Road
- Added Vehicle > Passengers
- Added World > Teleportation > Short Distances > Up
- Added World > Teleportation > Short Distances > Down
- Added World > Inhabitants > Vehicles > Traffic > Vehicle Manager > Launch Forward
- Renamed World > NPCS to World > Inhabitants
- Fixed Vehicle > Movement > Max Speed being set to 1944 instead of 540 by default (It goes back to normal if you change its value) and made it so if your game measurement system is set to KPH, then it will change your max speed in KPH, and MPH in MPH.
- Fixed Vehicle > Los Santos Customs > <vehicle> > Change Display Name only changing the name for one frame
- Fixed some bugs


# Version 11.1.3 (Legacy)
# Version 1.4 (Enhanced)
- Added World > Atmosphere > Clock > Use Freemode Time
- Added World > Atmosphere > Clock > Speed
- Removed Game > Info Overlay > Playing Time
- Removed Game > Info Overlay > Time Since Last Death
- Removed Game > Info Overlay > Time Since Last Arrest
- Fixed Game > Info Overlay > FPS Showing an incorrect value when using a character's special ability and made it so it only updates every 300ms so you can actually read the frame rate.
- Fixed the entirety of “Self” disappearing if you tried to register a vehicle that does not exist in Vehicle > Los Santos Customs
- Fixed Vehicle > Movement > Max Speed not allowing you to set your speed over 540
- Made it so it tells you what your current vehicle is in Los Santos Customs, and also draws a beacon the vehicle that is selected in the menu
- Made it so in World > Teleportation > Saved Places, when a place is selected a beacon will be drawn to it
- Did the same thing as above for IPLS
- Made smooth scrolling adjust for your frame rate, instead of being too slow or too fast because it was fixed for 60fps


# Version 11.0.0 (Legacy)
# Version 1.3 (Enhanced)
- Added World > Draw Beacon To… > Include Dead NPCS
- Added SaturnV > Quick Alt + F4
- Improved Vehicle > Los Santos Customs
- Renamed World > Beacon Manager to Draw Beacon To…
- Moved Game > Info Overlay > Cops > Draw Beacon To Nearest Cop to World > Draw Beacon To…
- Replaced World > Draw Beacon To… > Beacon Type with a text slider
- Made beacons draw to inhabitants regardless if they are in a vehicle or not
- Added minor UI changes
- Added a detection if the process is invalid, eg your running SaturnV legacy in GTA enhanced, the menu wont run and your gta will shut in 5 seconds
- Readded online checks, will do the same as above


# Version 10.9.2 (Legacy)
# Version 1.1 (Enhanced)
- Fixed no value being set when entering a value on sliders via the text box
- Made Vehicle > Bulletproof Tires fix your tires when toggled on


# Version 1.0 (Enhanced)
- Released SaturnV for GTA5 Enhanced
- Added 5 new Enhanced only cars


# Version 10.8.3 (Legacy)
- Added Vehicle > Spawner > Licence Plate
- Added Vehicle > Los Santos Customs > <Vehicle> > Livery (Only shows if the vehicle has any liverys)
- Added Vehicle > Los Santos Customs > <Vehicle> > Options > Change Licence Plate
- Added more accurate mod type names, like for motorcycles instead of “Roof” it will say “Saddle Bags” for example
- Removed the option to change your wheels if you registered a helicopter in Vehicle > Los Santos Customs
- Made it so when registering a vehicle with Vehicle > Los Santos Customs, if the manufacturer name doesn’t exist and you chose to include the manufacturer names in the settings, it will just say the vehicle name, like “NULL Police Cruiser” - “Police Cruiser”
- Upgraded the input controller and added auto scroll for sliders


# Version 10.7.1 (Legacy)
- Added World > Beacon Manager > Beacon Type
- Added World > IPLS
- Added World > IPLS > North Yankton
- Added World > IPLS > Cayo Perico
- Added World > IPLS > Red Carpet
- Added World > IPLS > Aircraft Carrier
- Added World > IPLS > Train Wreck
- Added World > IPLS > FIB Lobby
- Added World > NPCS > Traffic > Vehicle Manager > Delete
- Added Game > Info Overlay > Time Since Last Death
- Added Game > Info Overlay > Time Since Last Arrest
- Fixed Info Overlays not drawing with the menu was toggled off
- Made it so if you have the text box open and press 'F' and have Instantly Enter/Exit Vehicles on, it wont do anything
- Added smooth scrolling


# Version 10.5.1 (Legacy)
The menu has had a bit of a refresh, and I was updating it for so long that I forgot to document the features I added, however around 30 - 40 were added.


# Version 3.5 (Legacy)
- Vehicle > Movement
- Vehicle > Movement > Handbrake
- Vehicle > Movement > Drift Mode
- Vehicle > Instantly Enter/Exit Vehicles
- World > Atmosphere > Gravity 0 -3
- Game > Minimap > Fullscreen Map
- Added a short cooldown between starting and stopping a lua script (1 second) because if you spam start/stop it will crash your game
- Added a proper clean up when turning off a lua script
- Made error catching on lua better
- Moved some vehicle options related to movement to Vehicle > Movement
- Fixed the unknown cheats link directing you to youtube
- Fixed some crashes and bugs
- Fixed an issue with text slider default options
- Fixed some spelling errors
- If you load SaturnV with another ScriptHookV DLL (E.g. through a mod menu), when you unload the menu, it will now fully unload instead of leaving some features on
- Lua - Version 1.35
- Added entities.delete(handle), see https://github.com/nbz1559/SaturnV-Lua-Guide/blob/main/CHANGELOG.md for more info


# Version 3.3 (Legacy)
- Added a new panel, Scripting
- Moved everything from SaturnV > Lua Scripts to Scripting
- Fixed an issue with downloading Lua Scripts
- Replaced Scripting > <Lua Script> > Toggle Script With Start Script / Stop Script
- Upgraded UI in various ways

- Lua - Version 1.3
- Added hyper_link
- Added read_only
- Added node controlling
- Added Globals
- Added Clipboard functions
- see https://github.com/nbz1559/SaturnV-Lua-Guide/blob/main/CHANGELOG.md for more info

# Version 3.2 (Legacy)
- Fixed some UI Issues
- Removed Self > Glue To Seat (Due to it not working)
- World > Teleportation > Stunt Jumps
- World > Teleportation > Spaceship Parts
- World > Beacon Manager > Draw Beacon To Mission Entities
- World > Beacon Manager > Draw Beacon To Cars
- Made it so when you click enter on a text slider, it opens up a submenu for that text slider

- Lua - Version 1.25
- Added Slider Float, see https://github.com/nbz1559/SaturnV-Lua-Guide/blob/main/CHANGELOG.md for more info

# Version 3.1 (Legacy)
- Self > Glue To Seat
- Self > Movement > Tennis Mode
- World > Atmosphere > Force Lightning Flash
- World > World Light >
- World > World Light > Toggle Light
- World > World Light > R
- World > World Light > G
- World > World Light > B
- World > World Light > Range
- World > World Light > Intensity
- Game > Remove loading indicator
- Game > Minimap
- Game > Remove Notifications Above Minimap to Game > Minimap
- Game > Minimap > Hide Minimap
- Game > Minimap > Toggle big minimap
- Game > Minimap > Reveal entire map
- Game > Disable Stuff
- Game > Disable Stuff > Disable Stunt Jumps
- Game > Disable Stuff > Disable Cinematic Camera
- Game > Disable Stuff > Disable Idle Camera
- Made it so on sliders when you click on some, it will prompt you with the text box to enter a value.
- If sliders have the option for you to click it to run the command, below the menu it will say “Click to apply a value from minval - maxval”.
- If they have the option for you to click it to enter a value, below the menu it will say “Click to input a value from minval - maxval”


# Version 3.0 (Legacy)
- Vehicle > Increase Grip
- World > Teleportation > Places > Police Stations
- World > Teleportation > Places > Hospitals
- World > Teleportation > Places > Landmarks
- World > Teleportation > Very High
- Game > Remove Notifications Above Minimap
- Game > Achievements > – Achievements (0/77) – 
- Game > Rendering > AnimpostFX
- Added more teleport points in World > Teleportation > Places > Stores
- Added more teleport points in World > Teleportation > Places > Other
- Renamed World > Atmosphere > Clock > Set Time 00:00:00 to > Time 13:11:53 (It displays the actual time now)
- Moved everything in Game > Rendering > Screen Effects to Game > Rendering
- Moved all original locations inside of World > Teleportation > Places to World > Teleportation > Places > Other
- Moved all original locations inside of World > Teleportation > Stores to World > Teleportation > Places > Stores
- Made it so that Game > Achievements shows you which achievements you have completed
- Added more character support for the text box
- Added a flashing cursor to the text box
- Minor upgrades and changes to the UI
- Lua - Version 1.2
- See https://github.com/nbz1559/SaturnV-Lua-Guide/blob/main/CHANGELOG.md for more lua updates


# Version 2.8 (Legacy)
- Self > Appearance > No Blood
- World > Teleportation > Saved Places
- World > Teleportation > Saved Places > Open Folder
- World > Teleportation > Saved Places > Save Your Position
- World > Teleportation > Teleport To Position From Clipboard
- World > Teleportation > Save Position To Clipboard
- Renamed Self > Appearance > Model to Self > Appearance > Transform
- Removed Self > Glue to seat
- Improved World > NPCS > All NPCS > Kill
- Improved World > NPCS > Hostile NPCS > Kill
- Renamed Folder Names
- Luascripts > Lua Scripts
- No lua updates


# Version 2.7 (Legacy)
- Vehicle > Los Santos Customs > Settings
- Vehicle > Los Santos Customs > Settings > Registered Vehicle Dont Despawn
- Vehicle > Los Santos Customs > [Vehicle] > Options > Enter
- Vehicle > Los Santos Customs > [Vehicle] > Options > Teleport To Me
- Vehicle > Los Santos Customs > [Vehicle] > Options > Delete
- Vehicle > Helicopter Blade Speed
- Moved Game > Game State to World > Game State and renamed it to World State
- Fixed Vehicle > Bullet Proof Tires not working
- See https://github.com/nbz1559/SaturnV-Lua-Guide/blob/main/CHANGELOG.md for more lua updates


# Version 2.65 (Legacy)
- Self > Refill Health
- Self > Refill Armour
- Vehicle > No Turbulence
- Vehicle > Destroy Vehicle
- World > Blackout
- World > NPCS > Traffic > Traffic Colour
- World > Atmosphere > Clouds
- Game > Rendering
- See https://github.com/nbz1559/SaturnV-Lua-Guide/blob/main/CHANGELOG.md for more lua updates

# Version 2.6 (Legacy)
- Fixed some bugs
- See https://github.com/nbz1559/SaturnV-Lua-Guide/blob/main/CHANGELOG.md for more lua updates

# Version 2.5 (Legacy)
- Made it so Game > Auto remove black screen is now toggled off by default, as this could interfer with lua scripts
- Made it so if you try to open a submenu that has nothing inside it, the menu will refuse
- Lua has been released, you can now make your own custom scripts, view https://github.com/nbz1559/SaturnV-Lua-Guide/blob/main/README.md for more info


# Version 2.15 (Legacy)
- Fixed World > Teleportation > Teleportation type Character Swap again
- Mostly been working on lua


# Version 2.0 (Legacy)
- Self > Clumsiness
- Game > Info Overlay > Cops
- Game > Info Overlay > Cops - to Amount of cops
- Game > Info Overlay > Amount of cops to Game > Info Overlay > Cops
- Game > Info Overlay > Cops > Distance to nearest cop
- Game > Info Overlay > Cops > Draw beacon to nearest cop
- Fixes for World > Teleportation > Teleport Type Character Swap
- Fixed Waypoint teleport and Mission Objective teleport failing
- Fixed some bugs and improved the overall quality of the teleport
- Made it so it gets the ideal swap type (if in short distances, then a short swap for example)
- Readded Lua Scripting, SaturnV > Lua Scripts
- Information on how to make your own lua scripts will come out next update


# Version 1.7 (Legacy)
- Removed SaturnV > Profiles due to it not working, and right now i cant make them work with my system. It may be added back in a future update
- SaturnV > Settings > Appearance > Position
- SaturnV > Settings > Appearance > Colours
- SaturnV > Settings > Appearance > Colours > Header
- SaturnV > Settings > Appearance > Colours > Command panel
- SaturnV > Settings > Appearance > Colours > Options panel
- SaturnV > Settings > Appearance > Colours > Beacons
- SaturnV > Settings > Appearance > Colours > Info Overlay
- SaturnV > Credits
- SaturnV > Open SaturnV Folder
- SaturnV > Clear InfoLog.txt
- Changed World > Beacon Manager > Place beacon on vehicle - to - World > Beacon manager > Place beacon on Active Vehicle
- Changed Settings to SaturnV
- Relocated Settings to SaturnV > Settings
- Made it so when using World > Teleportation > Teleportation Type Character Swap, when the teleport is over, it will give you all the weapons in the game, because last update it left you with your fists
- Improved Auto-Scroll


# Version 1.6 (Legacy)
- Removed Scripting
- Vehicle > Trains
- Vehicle > Trains > Search For Trains
- World > Teleportation > Teleportation Type > Default
- World > Teleportation > Teleportation Type > Character Swap
- World > Beacon Manager
- More Info Overlays in Game > Info Overlay
- Settings > Profiles > Create Profile
- Settings > Profiles > <profile name> > Load Profile
- Settings > Profiles > <profile name> > Save Profile
- Settings > Profiles > <profile name> > Delete Profile
- Added a log, can be found in %appdata% SaturnV > InfoLog
- Not much is in the log yet, just telling you when the script has started/stopped
- Fixed the top bar incorrectly showing what submenu you are in
- Fixed Vehicle > Los Santos Customs


# Version 1.5 (Legacy)
- Scripting
- Scripting > Lua Scripts
- Scripting > Lua Scripts > Refresh
- Scripting > Lua Scripts > Open Folder


# Version 1.4 (Legacy)
- Game > Info Overlay > NPCS
- Game > Info Overlay > Vehicles
- Self > Movement > Movement Clipset
- Fixed World > NPCS > All NPCS and Hostile NPCS not including all npcs
- Fixed Game > Info Overlay > Cops not showing all cops


# Version 1.35 (Legacy)
- Self > Suicide
- Vehicle > Toggle engine On/Off
- World > Teleportation > Mission Objective
- Game > Visual Effects
- Game > Visual Effects > Night Vision
- Game > Visual Effects > Heat Vision
- Game > Visual Effects > Drunk Mode
- Game > Info Overlay > Cops Near You
- Fixed World > Teleportation > Waypoint not teleporting your vehicle
- Made toggles more reliable


# Version 1.3 (Legacy)
- Self > Appearance > Model > NPCS
- Self > Weapons > Get Weapons > Pistols
- Self > Weapons > Get Weapons > Smgs
- Self > Weapons > Get Weapons > Assault Rifles
- Self > Weapons > Get Weapons > Snipers
- Self > Weapons > Get Weapons > Melee Weapons
- Self > Weapons > Get Weapons > Shotguns
- Self > Weapons > Get Weapons > Heavy Weapons
- Self > Weapons > Get Weapons > Throwables
- Game > Info Overlay > Speed
- Game > Info Overlay > Altitude
- Game > Info Overlay > Time (Game)
- Game > Info Overlay > Player Health
- Game > Info Overlay > Engine Health
- Made Self > Weapons > Get Weapons > All Weapons actually give you all the weapons
- Upgraded UI
- Made the top bar show your position in the menu, like Saturn V 1.00 > Self > Weapons

# Version 1.25 (Legacy)
- World > NPCS
- World > NPCS > All NPCS
- World > NPCS > Hostile NPCS
- World > NPCS > Traffic > Disable Traffic
- World > NPCS > Traffic > Disable Foot Traffic
- World > Atmosphere > Clock
- Game > Game State > Online
- Game > Game State > Story Mode
- Made it so the menu wont detect input if GTA isnt focused
- Upgraded the text box


# Version 1.2 (Legacy)
- Self > Appearance > Model
- Self > Model > Playable Characters
- Self > Model > Land Animals
- Self > Model > Air Animals
- Self > Model > Sea Animals
- Vehicle > Los Santos Customs
- Game > Auto Remove Black screen (Auto toggled on)


# Version 1.15 (Legacy)
- Vehicle > Indestructible
- Removed Vehicle > Manage Vehicle (Replaced by Vehicle > Los Santos Customs in 1.2)
- Fixed Self > Invincibility randomly turning off
- Reduced file size

# Version 1.10 (Legacy)
- Self > Toggle Invisibility
- World > Atmosphere
- World > Atmosphere > Weather
- Game > Remove black screen
- Game > Money > Remove 100,000
- Game > Money > Remove 10,000
- Fixed needing to press F5 instead of F4 to open the menu


# Version 1.00 (Legacy)
On the release, the features were avalible
- Self > Weapons > Get Weapons > All Weapons
- Self > Weapons > Remove Weapons > All Weapons
- Self > Weapons > Infinite Ammo
- Self > Weapons > Perfect Accuracy
- Self > Invincibility
- Self > No Ragdoll
- Self > Cant be dragged out
- Self > Set Wanted Level 1 - 5
- Self > Lock Wanted Level
- Self > Set Fake Wanted Level 1 - 6
- Self > Glue To Seat
- Self > Infinite Stamina
- Self > Inifnite Special Ability
- Vehicle > Spawner > Vehicles > (Every vehicle was added in their classes but i wont list them, its too long)
- Vehicle > Spawner > Start With Engine On
- Vehicle > Spawner > Spawn In Vehicle
- Vehicle > Previous Vehicle > Enter
- Vehicle > Previous Vehicle > Teleport To Me
- Vehicle > Bulletproof Tires
- Vehicle > Engine Power Multiplier 1 - 50
- Vehicle > Fix
- Vehicle > Delete
- World > Teleportation > Waypoint
- World > Teleportation > Places
- World > Teleportation > Places > Maze Bank Tower
- World > Teleportation > Places > LSIA
- World > Teleportation > Places > Michaels House
- World > Teleportation > Places > Franklins New House
- World > Teleportation > Places > Auntie Denises House
- World > Teleportation > Places > Trevors Trailer
- World > Teleportation > Places > Floyd and Debras House
- World > Teleportation > Stores > Ammunation
- World > Teleportation > Stores > LS Customs
- World > Teleportation > Stores > Binco Clothing
- World > Teleportation > Stores > Suburban
- World > Teleportation > Stores > Ponsonbys
- Game > Skip Dialogue
- Game > Auto Skip Dialogue
- Game > Auto Skip Cutscene
- Game > Achievments (All achievements are listed but i wont list them, its too long)
- Game > Money > Set Cash <...>
- Game > Money > Add $1,000
- Game > Money > Add $10,000
- Game > Money > Add $100,000
- Game > Money > Add $1,000,000
- Game > Settings > Nothing to see here
