This Team Fortress 2 configuration prioritizes FPS and reduced visual clutter over graphical quality.

# Disclaimer
These commands use standard TF2 console variables. Some commands may have no effect on certain systems or TF2 versions. Test the configuration and adjust settings to your preference. Use at your own risk.

# Steam Launch Options (Must add them manually)
Recommended: ```-novid -nojoy -nosteamcontroller -nohltv -noff -noipx -high -console```

```-novid``` => Skips the Valve intro video when launching TF2 for a faster startup.

```-nojoy``` => Saves some resources by disabling joystick/gamepad input support.

```-nosteamcontroller``` => Disables support for the Steam Controller input system.

```-nohltv``` => Saves some resources by disabling half life tv support.

```-noff``` => Saves some resources by disabling controller vibration / haptics (not well documented!).

```-noipx``` => Saves some resources by disabling IPX protocol support (an old LAN networking protocol from the 1990s).

```-high``` => Sets the game process priority to High (Windows only).

```-console``` => Automatically opens the developer console on startup.

# Quality of Life Gameplay Changes
```tf_sniper_fullcharge_bell 1``` => The sniper rifle makes a bell sound when it is fully charged.

```tf_medigun_autoheal 1``` => The medigun functions like a toggle, meaning that there is no more need to hold MOUSE1 to heal a teammate.

```hud_fastswitch 1``` => Enables instant weapon switching without the selection confirmation step.

```cl_autoreload 1``` => Automatically reloads your weapon whenever it’s not full.

```fov_desired 90``` => Increases the field of view to the maximum available.

```viewmodel_fov 82``` => Balances how far your weapon model (hands + gun) appears from your camera.

# Quality of Life HUD Changes
```cl_disablehtmlmotd 1``` => Disables HTML-based “Message of the Day” (MOTD) pages that some community servers show.

```tf_item_inspect_model_auto_spin 0``` => Disables weapons from automatically rotating when inspecting them inside your inventory.

```tf_dashboard_slide_time 0``` => Disables slide animations for various dashboards and UI elements.

```cl_hud_minmode 1``` => Enables minimal HUD for a reduced in-game HUD.

```cl_spec_carrieditems 0``` => Disables viewing what items a player is carrying while spectating.

```cl_showbackpackrarities 0``` => Disables item rarities (colors/quality indicators) shown in your inventory.

```cl_show_market_data_on_items 0``` => Disables showing Steam Community Market pricing data on item tooltips.

```hud_combattext 1``` => Enables damage numbers when you hit enemies.

```hud_combattext_batching 1``` => Groups multiple damage numbers into a single combined.

```hud_combattext_batching_window 2``` => Defines the time window (in seconds) used for batching damage numbers.

# Additional Resources
Official commands list by Valve: https://developer.valvesoftware.com/wiki/List_of_Team_Fortress_2_console_commands_and_variables
