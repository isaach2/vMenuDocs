---
title: "Permissions Reference"
weight: 41
---

## List of ALL permissions

## Global Permissions

{{% notice info %}}
**1\)** __\*__ The `Default (allowed/denied)` values are based on the assumption that you use the default permissions file included with the menu, and you've granted yourself no special permissions or added yourself to any of the admin/moderator groups. If you **DON'T** use the default permissions file, then every option will be **DENIED** by default.
<br><br>**2\)** __\*\*__ These options are only allowed by default for the "Moderators" / "Admins" groups in the provided permissions file with this resource.
<br><br>**3\)** __\*\*\*__ When spawning a car using the `Spawn By Name` button, it will always check to see if you have permission for that specific vehicle's class. eg: If you don't have permission to spawn cars from the `Super` class, trying to spawn an `adder` using the `Spawn By Name` button won't work.
<br><br>**4\)** __\*\*\*\*__ Only admins are allowed to use this by default.
{{% /notice %}}


|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.Everything`|Grants access to everything, not recommended to give this out.|**Not** allowed|
|`vMenu.DontKickMe`|Prevents this player from being kicked.|**Not** allowed|
|`vMenu.DontBanMe`|Prevents this player from being banned.|**Not** allowed|
|`vMenu.NoClip`|Allows the user to use the NoClip feature.|Allowed|
|`vMenu.Staff`|If the `menu_staff_only` config option is enabled, then this permission is required to be able to use vMenu.|Allowed|

## Online Players

|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.OnlinePlayers.Menu`|Grants access to the Online Players Menu|Allowed|
|`vMenu.OnlinePlayers.All`|Grants access to **ALL** `Online Players Menu` options.|**Not** allowed|
|`vMenu.OnlinePlayers.Teleport`|Allows you to teleport to another player.|Allowed|
|`vMenu.OnlinePlayers.Waypoint`|Allows you to set a waypoint to another player.|Allowed|
|`vMenu.OnlinePlayers.Spectate`|Allows you to spectate another player.|Allowed|
|`vMenu.OnlinePlayers.Identifiers`|Allows you to see the identifiers of a player in-game. (Allowed by default for admins only)|Allowed\*|
|`vMenu.OnlinePlayers.Summon`|Allows you to summon/teleport another player to you. (Default: moderators only)|**Not** allowed|
|`vMenu.OnlinePlayers.Kill`|Allows you to kill another player by pressing a button. Dam, you're very cruel. (Default: moderators only)|**Not** allowed|
|`vMenu.OnlinePlayers.Kick`|Allows you to kick another player from the server. (Default: moderators only)|**Not** allowed|
|`vMenu.OnlinePlayers.TempBan`|Allows you to ban the player from the server for a custom amount of time, max temp-ban duration: 30 days. (Default: admins only)|Denied\*|
|`vMenu.OnlinePlayers.PermBan`|Allows you to ban the player from the server forever. (Default: admin only)|Denied\*\*\*\*|
|`vMenu.OnlinePlayers.ViewBannedPlayers`|Allows you to see a list of banned players, does not allow you to unban players. (Allowed by default for moderators)|**Not** allowed|
|`vMenu.OnlinePlayers.Unban`|Allows you to access the "Banned Players" menu to view and unban banned players. (The menu is not actually located in the "Online Players menu", it's in the main menu instead. It is still part of "user management" and thus the permission node is related to "Online Players"). (Allowed by default for admins)|**Not** allowed|
|`vMenu.OnlinePlayers.SeePrivateMessages`|Allows you to see _all_ private messages that players send to each other. Not allowed for _anyone_ by default.|**Not** allowed|

## Player Options

|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.PlayerOptions.Menu`|Grants access to the Player Options Menu.|Allowed|
|`vMenu.PlayerOptions.All`|Grants access to **ALL** `Player Options Menu` options.|Allowed|
|`vMenu.PlayerOptions.God`|Allows you to use god mode.|denied|
|`vMenu.PlayerOptions.Invisible`|Allows you to go invisble.|denied|
|`vMenu.PlayerOptions.UnlimitedStamina`|Allows you to go enable/disable unlimited stamina so you don't take damage after sprinting for 2 seconds.|Allowed|
|`vMenu.PlayerOptions.FastRun`|Allows you to enable Fast Run.|denied|
|`vMenu.PlayerOptions.FastSwim`|Allows you to enable Fast Swim.|denied|
|`vMenu.PlayerOptions.Superjump`|Allows you to enable Superjump.|denied|
|`vMenu.PlayerOptions.NoRagdoll`|Allows you to enable No Ragdoll.|Allowed|
|`vMenu.PlayerOptions.NeverWanted`|Allows you to enable Never Wanted.|Allowed|
|`vMenu.PlayerOptions.SetWanted`|Allows you to set a custom wanted level.|Allowed|
|`vMenu.PlayerOptions.Ignored`|Allows you to enable the Everyone Ignores Player option.|Allowed|
|~~`vMenu.PlayerOptions.Functions`~~|~~Allows you to access some basic functions like healing, cleaning clothes, dry/wet clothes, commit suicide, etc.~~ **Removed in v1.5.0**|~~Allowed~~|
|`vMenu.PlayerOptions.MaxHealth`|This allows the player to heal themselves in the Player Options menu.|Allowed|
|`vMenu.PlayerOptions.MaxArmor`|This allows the player to give themselves max armor in the Player Options menu.|Allowed|
|`vMenu.PlayerOptions.CleanPlayer`|This allows the player to clean their player clothes in the Player Options menu.|Allowed|
|`vMenu.PlayerOptions.DryPlayer`|This allows the player to make their clothes dry in the Player Options menu.|Allowed|
|`vMenu.PlayerOptions.WetPlayer`|This allows the player to make their clothes wet in the Player Options menu.|Allowed|
|`vMenu.PlayerOptions.VehicleAutoPilotMenu`|This allows the player to use the vehicle auto pilot options, which is located in the Player Options menu.|Allowed|
|`vMenu.PlayerOptions.Freeze`|Allows you to freeze your own player. Why would you need to do this though...|Allowed|
|`vMenu.PlayerOptions.Scenarios`|Allows you to play and stop scenarios.|Allowed|
|`vMenu.PlayerOptions.StayInVehicle`|Gives you access to the "stay in vehicle" option that prevents you from being dragged out of your vehicle.|Allowed|

## Vehicle Options

|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.VehicleOptions.Menu`|Grants access to the Vehicle Options Menu.|Allowed|
|`vMenu.VehicleOptions.All`|Grants access to **ALL** `Vehicle Options Menu` options.|Allowed|
|`vMenu.VehicleOptions.God`|Allows you to enable vehicle godmode.|denied|
|`vMenu.VehicleOptions.BikeSeatbelt`|Allows you to enable bike seatbelt preventing you from falling off your motorcycle if you crash.|Allowed|
|`vMenu.VehicleOptions.KeepClean`|Allows you to toggle the 'keep clean' function.|Allowed|
|`vMenu.VehicleOptions.Repair`|Allows you to repair your vehicle.|denied|
|`vMenu.VehicleOptions.Wash`|Allows you to wash/clean your vehicle & set a custom dirt level.|Allowed|
|`vMenu.VehicleOptions.Engine`|Allows you to toggle your engine on/off.|Allowed|
|`vMenu.VehicleOptions.SpeedLimiter`|Allows you to limit your vehicle's speed.|Allowed|
|`vMenu.VehicleOptions.ChangePlate`|Allows you to change your vehicle's license plate style & text.|Allowed|
|`vMenu.VehicleOptions.Mod`|Allows you to modify any visual and performance specs of your vehicle.|Allowed|
|`vMenu.VehicleOptions.Colors`|Allows you to change the color of your vehicle.|Allowed|
|`vMenu.VehicleOptions.Liveries`|Allows you to change the livery of your vehicle.|Allowed|
|`vMenu.VehicleOptions.Components`|Allows you to modify the components/extras of your vehicle.|Allowed|
|`vMenu.VehicleOptions.Doors`|Allows you to open/close vehicle doors using the menu.|Allowed|
|`vMenu.VehicleOptions.Windows`|Allows you to roll up/down your windows using the menu.|Allowed|
|`vMenu.VehicleOptions.Freeze`|Allows you to freeze the position of your vehicle (why would you do this though...)|Allowed|
|`vMenu.VehicleOptions.TorqueMultiplier`|Allows you to set and enable an engine torque multiplier.|denied|
|`vMenu.VehicleOptions.PowerMultiplier`|Allows you to set and enable an engine power multiplier.|denied|
|`vMenu.VehicleOptions.Invisible`|Allows you to toggle vehicle visibility.|Allowed|
|`vMenu.VehicleOptions.InfiniteFuel`|Allows you to enable infinite vehicle fuel (requires FRFuel to be installed).|Allowed|
|`vMenu.VehicleOptions.Flip`|Allows you to flip your vehicle if it's upside down.|Allowed|
|`vMenu.VehicleOptions.Alarm`|Allows you to toggle the vehicle's alarm on/off. Turning it on will randomize the alarm duration between 8-30 seconds.|Allowed|
|`vMenu.VehicleOptions.CycleSeats`|Allows you to cycle through all available vehicle seats.|Allowed|
|`vMenu.VehicleOptions.EngineAlwaysOn`|Allows you to enable the Engine Always On feature, this keeps the engine running when you exit your vehicle.|Allowed|
|`vMenu.VehicleOptions.NoSiren`|Allows you to disable the siren on the vehicle.|Allowed|
|`vMenu.VehicleOptions.NoHelmet`|Allows you to disable the "automatically equipped" helmets when getting on a bike.|Allowed|
|`vMenu.VehicleOptions.Lights`|Allows you to enable/disable specific vehicle lights like hazard lights, turn signals, interior lighting, taxi lights or helicopter spotlights.|Allowed|
|`vMenu.VehicleOptions.Delete`|Allows you to delete your current vehicle.|Allowed|
|`vMenu.VehicleOptions.Underglow`|Allows you to access the vehicle underglow options submenu.|Allowed|
|`vMenu.VehicleOptions.FlashHighbeamsOnHonk`|Allows you to enable/disable the 'Flash highbeams on Honk' option.|Allowed|
|`vMenu.VehicleOptions.DisableTurbulence`|Allows you to disable plane turbulence. Only works for planes.|Allowed|
|`vMenu.VehicleOptions.FixOrDestroyTires`|Allows you to use the tire fix/destroy list option to fix or destroy specific vehicle tires through the menu.|Allowed|
|`vMenu.VehicleOptions.Flares`|Unused for now.|N/A|
|`vMenu.VehicleOptions.PlaneBombs`|Unused for now.|N/A|

## Vehicle Spawner

|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.VehicleSpawner.Menu`|Grants access to the Vehicle Spawner Menu.|Allowed|
|`vMenu.VehicleSpawner.All`|Allows you to spawn **ANY** vehicle.|Allowed|
|`vMenu.VehicleSpawner.DisableReplacePrevious`|Allows you to disable the "Replace Previous" vehicle option, if this is not allowed, then the option will be forced on.|Allowed|
|`vMenu.VehicleSpawner.SpawnByName`|Allows you to enter a **custom vehicle name** to spawn[\*\*\*](#global-permissions).|Allowed|
|`vMenu.VehicleSpawner.Addon`|Allows you to spawn a vehicle from the Addon Vehicles list (requires vMenu v1.0.7+).|Allowed|
|`vMenu.VehicleSpawner.Compacts`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Sedans`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.SUVs`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Coupes`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Muscle`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.SportsClassic`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Sports`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Super`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Motorcycles`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.OffRoad`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Industrial`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Utility`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Vans`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Cycles`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Boats`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Helicopters`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Planes`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Service`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Emergency`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Military`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Commercial`|Allows you to spawn a vehicle from this category.|Allowed|
|`vMenu.VehicleSpawner.Trains`|Allows you to spawn a vehicle from this category.|Allowed|

## Saved Vehicles

|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.SavedVehicles.Menu`|Grants access to the Saved Vehicles Menu.|Allowed|
|`vMenu.SavedVehicles.All`|Grants access to **ALL** `Saved Vehicles Menu` options.|Allowed|
|`vMenu.SavedVehicles.Spawn`|Allows you to spawn one of your saved cars. Saving new cars or deleting existing saved cars is always allowed no matter what.|Allowed|

## Personal Vehicle

|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.PersonalVehicle.Menu`|Allows you to use the menu and set a vehicle as your personal vehicle.|Allowed|
|`vMenu.PersonalVehicle.All`|Grants access to **ALL** `Personal Vehicle Menu` options.|Allowed|
|`vMenu.PersonalVehicle.ToggleEngine`|Allows you to toggle the engine remotely for your personal vehicle.|Allowed|
|`vMenu.PersonalVehicle.ToggleLights`|Allows you to toggle the lights state remotely for your personal vehicle.|Allowed|
|`vMenu.PersonalVehicle.KickPassengers`|Allows you to kick all passengers from your vehicle, they will have a 10 second timer to stop the vehicle if they’re driving it. If they refuse to stop then they will be forcefully kicked out of the vehicle after 10 seconds. If they do stop the vehicle within those 10 seconds they’ll automatically be tasked to get out of the vehicle.|Allowed|
|`vMenu.PersonalVehicle.LockDoors`|This allows you to lock and unlock your personal vehicle’s doors for all players. Anyone inside the vehicle is still able to get out of the vehicle if the doors get locked. If you are close to the vehicle, you can quickly double tap E on keyboard or L3 on controller (the vehicle horn button) to toggle locking/unlocking your doors.|Allowed|
|`vMenu.PersonalVehicle.AddBlip`|Allows you to add a blip for your personal vehicle.|Allowed|
|`vMenu.PersonalVehicle.SoundHorn`|Allows you to remotely sound the horn for 1 second. Fucks up if you’re inside the vehicle, so only use it whenever you’re outside of the vehicle for the best effect.|Allowed|
|`vMenu.PersonalVehicle.ToggleAlarm`|Remotely toggles the alarm on/off.|Allowed|
|`vMenu.PersonalVehicle.ExclusiveDriver`|Allows you to be the exclusive driver of the vehicle, preventing other players from getting into the driver's seat.|Allowed|

## Player Appearance

|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.PlayerAppearance.Menu`|Grants access to the Player Appearance Menu.|Allowed|
|`vMenu.PlayerAppearance.All`|Grants access to **ALL** `Player Appearance Menu` options.|Allowed|
|`vMenu.PlayerAppearance.Customize`|Allows you to customize your current ped.|Allowed|
|`vMenu.PlayerAppearance.SpawnSaved`|Allows you to spawn a saved ped. Saving new peds or deleting existing saved peds is always allowed no matter what.|Allowed|
|`vMenu.PlayerAppearance.SpawnNew`|Allows you to spawn any ped model from a list.|Allowed|
|`vMenu.PlayerAppearance.AddonPeds`|Allows you to spawn any addon ped model from a addon peds list.|Allowed|

## Time Options

|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.TimeOptions.Menu`|Grants access to the Time Options Menu.|Denied[\*\*](#global-permissions)|
|`vMenu.TimeOptions.All`|Grants access to **ALL** `Time Options Menu` options.|**Not** allowed|
|`vMenu.TimeOptions.FreezeTime`|Allows you to freeze the current time. (Synced for everyone in the server)|Denied[\*\*](#global-permissions)|
|`vMenu.TimeOptions.SetTime`|Allows you to set the current time. (Synced for everyone in the server)|Denied[\*\*](#global-permissions)|

## Weather Options

|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.WeatherOptions.Menu`|Grants access to the Weather Options Menu.|Denied[\*\*](#global-permissions)|
|`vMenu.WeatherOptions.All`|Grants access to **ALL** `Weather Options Menu` options.|**Not** allowed|
|`vMenu.WeatherOptions.Dynamic`|Allows you to enable/disable dynamic weather changes (which, when enabled, occur every 5 minutes). (Synced for everyone in the server)|Denied[\*\*](#global-permissions)|
|`vMenu.WeatherOptions.Blackout`|Allows you to enable/disable blackout mode (all light sources in the map go dark). (Synced for everyone in the server)|Denied[\*\*](#global-permissions)|
|`vMenu.WeatherOptions.SetWeather`|Allows you to set a custom weather type. (Synced for everyone in the server)|Denied[\*\*](#global-permissions)|
|`vMenu.WeatherOptions.RemoveClouds`|Allows you to remove all cloud effects (only use this with Clear or Extra Sunny weather, obviously). (Synced for everyone in the server)|Denied[\*\*](#global-permissions)|
|`vMenu.WeatherOptions.RandomizeClouds`|Allows you to randomize the cloud patterns/effects. (Synced for everyone in the server)|Denied[\*\*](#global-permissions)|

## Weapon Options
**Adding/Removing/Customizing any weapon is automatically _ALLOWED_ when you give the player permissions to access this menu.**

|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.WeaponOptions.Menu`|Grants access to the Weapon Options Menu.|Allowed|
|`vMenu.WeaponOptions.All`|Grants access to all `Weapon Options Menu` options.|Allowed|
|`vMenu.WeaponOptions.GetAll`|Allows you to use the `Get All Weapons` button.|Allowed|
|`vMenu.WeaponOptions.RemoveAll`|Allows you to use the `Remove All Weapons` button.|Allowed|
|`vMenu.WeaponOptions.UnlimitedAmmo`|Allows you to enable/disable unlimited ammo.|Allowed|
|`vMenu.WeaponOptions.NoReload`|Allows you to enable/disable no-reload.|Allowed|
|`vMenu.WeaponOptions.Spawn`|Allows you to spawn/remove ANY weapon, denying this will still grant access to the customization options for each weapon. This also allows players to spawn addon weapons.|Allowed|
|`vMenu.WeaponOptions.SpawnByName`|Allows you to spawn allowed weapons by entering their name.|Allowed|
|`vMenu.WeaponOptions.SetAllAmmo`|Allows you to bulk set the ammo count in all currently equipped weapons.|Allowed|

**For a list of individual weapon permissions check [this link](/vmenu/permissions-ref/weapon-permissions).**

## Weapon Loadouts

|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.WeaponLoadouts.Menu`|Grants access to the Weapon Loadouts Menu|Allowed|
|`vMenu.WeaponLoadouts.All`|Grants access to **ALL** Weapon Loadouts Menu options.|Allowed|
|`vMenu.WeaponLoadouts.Equip`|Allows you to equip a saved weapon loadout, will not allow weapons that are not allowed by permissions setup for weapon options menu.|Allowed|
|`vMenu.WeaponLoadouts.EquipOnRespawn`|Allows you to automatically equip a saved loadout whenever you (re)spawn, even on first join.|Allowed|

## Voice Chat

|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.VoiceChat.Menu`|Grants access to the Voice Chat Options Menu|Allowed|
|`vMenu.VoiceChat.All`|Grants access to **ALL** `Voice Chat Options Menu` options.|**Not** allowed|
|`vMenu.VoiceChat.Enable`|Allows you to enable/disable voice chat.|Allowed|
|`vMenu.VoiceChat.ShowSpeaker`|Allows you to enable/disable the "Currently Talking" display at the top of your screen when someone is using voice chat.|Allowed|
|`vMenu.VoiceChat.StaffChannel`|Allows you to enter the staff-only voice channel.|Denied[\*\*](#global-permissions)|

## Misc Settings

**The `Save Personal Settings` option in the Misc Settings Menu is always allowed, so there's no permission line for that. Also the menu itself does not have a permisison to access it, for the same reason why saving preferences is always allowed.**

|Permission|Description|Default[\*](#global-permissions)|
|---|---|---|
|`vMenu.MiscSettings.All`|Grants access to **ALL** `Misc Settings Menu` options.|**Not Allowed**|
|`vMenu.MiscSettings.ClearArea`|Allows you to reset/clear everything 100m around you in the world.|Allowed|
|`vMenu.MiscSettings.TeleportToWp`|Allows you to teleport to the waypoint on your map.|Allowed|
|`vMenu.MiscSettings.ShowCoordinates`|Allows you to show your current coordinates on screen.|Allowed|
|`vMenu.MiscSettings.ShowLocation`|Allows you to show your current location on screen (pretty much just like PLD).|Allowed|
|`vMenu.MiscSettings.JoinQuitNotifs`|Allows you to receive join/quit notifications when someone joins/quits the server.|Allowed|
|`vMenu.MiscSettings.DeathNotifs`|Allows you to receive death notifications when someone dies or gets killed.|Allowed|
|`vMenu.MiscSettings.NightVision`|Allows you to toggle night vision on/off.|Allowed|
|`vMenu.MiscSettings.ThermalVision`|Allows you to toggle thermal vision on/off.|Allowed|
|`vMenu.MiscSettings.LocationBlips`|Allows you to enable pre-defined map location blips, configured in the locations.json file.|Allowed|
|`vMenu.MiscSettings.PlayerBlips`|Allows you to show player blips.|Allowed|
|`vMenu.MiscSettings.OverheadNames`|Allows you to show player overhead names.|Allowed|
|`vMenu.MiscSettings.TeleportLocations`|Allows you to teleport to pre-configured locations, configured in the locations.json file.|Allowed|
|`vMenu.MiscSettings.ConnectionMenu`|Allows you to use the "Connection Options" menu (things like, disconnect from server, quit the game and "disconnect from session").|Allowed|
|`vMenu.MiscSettings.RestoreAppearance`|Allows you to enable this option in the Misc Settings menu, which will restore your player ped/skin whenever your ped dies and respawns. Will not restore the ped if you (re)join. **(only in vMenu v1.5.0 and up)**|Allowed|
|`vMenu.MiscSettings.RestoreWeapons`|Allows you to enable this option in the Misc Settings menu, which will restore your weapons whenever your ped dies and respawns. Will not restore the weapons if you (re)join. **(only in vMenu v1.5.0 and up)**|Allowed|
|`vMenu.MiscSettings.DriftMode`|Allows you to enable the drift mode keybind option in the misc settings menu.|Allowed|
|`vMenu.MiscSettings.TeleportSaveLocation`|Allows you to save a new location to the "Teleport Locations" menu, which will also get saved to the locations.json file. (not allowed by default if you use the new permissions.cfg in this update, otherwise EVERYONE may be able to use this so be careful!)|**Not Allowed**|
|`vMenu.MiscSettings.TeleportToCoord`|Allows you to teleport to any coordinate you enter.|Allowed|
|`vMenu.MiscSettings.EntitySpawner`|Allows you to use the entity spawner option inside Misc Settings > Developer Tools.|**Not Allowed**|



## About Submenu
The **About vMenu** submenu is always available for everyone, and can not be disabled with the use of permissions. If you don't feel like showing credits to everyone --which seems very selfish to me-- then you'll have to edit the code and disable it yourself, which also means I won't be giving you any support whatsoever.

## Appreciate my work?
Consider supporting me on [<i class='fab fa-patreon'></i> Patreon](https://www.patreon.com/vespura)!
