I - Description
I made this plugin for my community Zombie4Ever.eu and was allowed to share it.
Will show the damage on the Hint(HUD). 
Will show you the damage, armor and the part of the body.
For Molotov and Grenade you will get the total victim hurted with of course the damage and armor.
If you make a double, triple, or whatever kills you will get total victim hurted with of course the damage and armor.
The time(reset) between each kill is set by type of weapons(pistols, snipers, rifles...) and this timer can be set with cvars.
For the clients preferences type !sd in chat.

II - Cvars
drapi_show_damage_sniper_time - SNIPERS Time Between shots.
drapi_show_damage_mg_time - MACHINES GUNS Time Between shots.
drapi_show_damage_rifle_time - RIFLES Time Between shots.
drapi_show_damage_mp_time - MPS Time Between shots.
drapi_show_damage_pump_time - PUMPS Time Between shots.
drapi_show_damage_pistol_time - PISTOLS Time Between shots.

If you set a high value time the damage, armor and victim on the HUD will increase. 0.5s between it's enough to get double, triple... kills instant. If you shot the same victim twice it's count like one so don't worry if you set high value time.

III - Configs
"ShowDamage"
{
	"ShowDamage"
	{

		"ShowDamageAccess"
		{
			//EXAMPLE
			//"0"
			//{
				//"flags"		"steamid"										// flag for use the show damage(public, vip, admin, steamid)

				//"SteamIDs" 													// or steamids allowed to use the show damage(can be use with steamid, vip or admin flags)
				//{
							//"1"		"STEAM_1:1:4489913"
				//}

			//}

			"1"															//MOLOTOV
			{
				"flags"			"public"										// flag for use the show damage (public, vip, admin, steamid)

				"SteamIDs" 													// or steamids allowed to use the show damage(can be use with steamid, vip or admin flags)
				{
				}

			}

			"2"															//GRENADE
			{
				"flags"			"public"										// flag for use the show damage (public, vip, admin, steamid)

				"SteamIDs" 													// or steamids allowed to use the show damage(can be use with steamid, vip or admin flags)
				{
				}

			}

			"3"															//SNIPERS
			{
				"flags"			"steamid"										// flag for use the show damage (public, vip, admin, steamid)

				"SteamIDs" 													// or steamids allowed to use the show damage(can be use with steamid, vip or admin flags)
				{
				}

			}

			"4"															//MACHINE GUNS
			{
				"flags"			"public"										// flag for use the show damage (public, vip, admin, steamid)

				"SteamIDs" 													// or steamids allowed to use the show damage(can be use with steamid, vip or admin flags)
				{
				}

			}

			"5"															//RIFLES
			{
				"flags"			"public"										// flag for use the show damage (public, vip, admin, steamid)

				"SteamIDs" 													// or steamids allowed to use the show damage(can be use with steamid, vip or admin flags)
				{
				}

			}

			"6"															//PMs
			{
				"flags"			"public"										// flag for use the show damage (public, vip, admin, steamid)

				"SteamIDs" 													// or steamids allowed to use the show damage(can be use with steamid, vip or admin flags)
				{
				}

			}

			"7"															//PUMP
			{
				"flags"			"public"										// flag for use the show damage (public, vip, admin, steamid)

				"SteamIDs" 													// or steamids allowed to use the show damage(can be use with steamid, vip or admin flags)
				{
				}

			}

			"8"															//PISTOLS
			{
				"flags"			"public"										// flag for use the show damage (public, vip, admin, steamid)

				"SteamIDs" 													// or steamids allowed to use the show damage(can be use with steamid, vip or admin flags)
				{
				}

			}

			"9"															//OTHERS
			{
				"flags"			"public"										// flag for use the show damage (public, vip, admin, steamid)

				"SteamIDs" 													// or steamids allowed to use the show damage(can be use with steamid, vip or admin flags)
				{
				}

			}

		}
	}
}
You can now give access to each type of weapons (pistols, rifles, snipers, etc...).
- Admin and/or steamid
- Vip and/or steamid
- Steamid
- Public



IV - Changelogs
V1.1.2
-Personal Timer for showind damage. Should reduce the HUD time display.

V1.1.1
-Fixed a error log.

V1.1.0
-added config file to set the access of type of weapons.

V1.0.1
-Added clients preferences.
-Added some translations sentences.