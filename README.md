# Disclaimer
The commands provided in the autoexec.cfg are not officially approved by Valve and might generate crashes, glitches or undesired behabiour. Use them at your own risk.

# Read Before Use!
This autoexec.cfg comes with a default fps limit at 60. To change it please follow the next steps:
- Open the autoexec with notepad or any text editor.
- Under the general section, find the title "LIMIT FRAMES PER SECOND".
- Inside it, change the "fps_max 60" command to "fps_max {desired limit}"
- If you are using the steam launch commands this autoexec.cfg file provides. You must also change the "-freq 60" to "-freq {monitors refresh rate}"
- E.G.: "fps_max 120" & "-freq 120" (fps capped at 120 and refresh rate set to 120)
- E.G.: "fps_max 0" & "-freq 144" (fps uncapped and refresh rate set to 144)

# Gameplay Changes
- The sniper rifle makes a bell sound when it is fully charged (tf_sniper_fullcharge_bell 1).
- The medigun functions like a toggle, meaning that there is no more need to hold MOUSE1 to heal a teammate (tf_medigun_autoheal 1).
- The switch weapon hud is changed to disable the confirmation of a weapon switch (hud_fastswitch 1).
- Weapons now automatically reload (hud_fastswitch 1).

# Thanks
Thanks for giving them a try. Here I leave the official commands list by Valve: https://developer.valvesoftware.com/wiki/List_of_Team_Fortress_2_console_commands_and_variables
