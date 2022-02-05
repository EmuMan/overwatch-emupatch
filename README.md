# Overwatch EmuPatch

A custom patch for Overwatch with several toggleable changes to hero abilities, meant for both balance and entertainment. Please note that this is still in development and will likely have plenty of bugs and strange interactions even as time goes on, simply due to its nature as a workshop script.

## Usage

This code is written in [Deltin's OSTW language](https://github.com/ItsDeltin/Overwatch-Script-To-Workshop), so it has to be compiled with the associated VS Code extension before use. Alternatively, you can find the most recent version already compiled [here](https://pastebin.com/raw/492p6RSx). Simply copy all of the text on the page to your clipboard, and click the button shown below in Overwatch to load the gamemode and workshop settings.

![Overwatch Paste Workshop Code Button](https://user-images.githubusercontent.com/23511921/148482375-516ad5d2-0c0b-46c8-a3c9-650392a293c5.png)

Once this project reaches an acceptable level of features, I will generate a proper code for it and update that instead. For now, the above method is easiest.

## Changes

All of the changes listed below can be toggled through the workshop settings to fit your preferences. Changes marked with a (*) must instead be modified in their respective hero settings.

### D.Va

- Defense Matrix usage rate increased by 15% (*)

### Orisa

- Can now be mounted like a horse with the Interact key, and dismounted with the Crouch key
- Movement speed increased by 30% while not using Fortify
- Damage falloff added to Fusion Driver, starting at 10 meters (11 damage) and stopping at 30 meters (5 damage)
- Protective Barrier health decreased from 600 to 500 hit points
- Protective Barrier cooldown decreased from 6 to 5 seconds

### Reinhardt

- Charge can now be ended early by pressing the Charge key a second time
- Fire Strike now has two charges
- Fire Strike damage decreased from 100 to 80
- Reinhardt will now always be full throttling forwards, regardless of user input (off by default)

### Roadhog

- Take a Breather damage reduction reduced from 50% to 40%
- Chain Hook damage increased from 30 to 40
- Scrap Gun pellet damage decreased from 6.6 to 6
- Scrap Gun rate of fire decreased by 20%

### Sigma

- Experimental Barrier health decreased from 700 to 600 hit points
- Experimental Barrier recharge rate increased from 80 to 100 hit points per second (*)

### Winston

- Primal Rage max health increased from 1000 to 1500
- Jump Pack cooldown decreased from 6 to 5 seconds outside of Primal Rage

### Wrecking Ball

- Quad Cannons clip size reduced from 80 to 70

### Zarya

- Projected Barrier now has two charges (but only one Projected Barrier may be active at a time)

### Doomfist

- Now has 50% knockback resistance while using any abilities
- Now gains 15 more shields per ability landed with the maximum shields increased from 150 to 200 and the shield decay rate increased from 3 per second to 4 per second
- Rocket Punch can now knock a Bastion out of Sentry mode with reduced knockback and no wall collision damage

### Echo

- An Echo killed while using Duplicate is no longer able to transform back and instead suffers a true death

### Mei

- Cryo-Freeze now instantly kills anyone Mei directly falls on while using it
- Cryo-Freeze now has a 5% chance to backfire and kill Mei when activated (off by default)
- Opponents will no longer become frozen after extended contact with Mei's Endothermic Blaster
- Mei's Ultimate now transforms her into a rolling snowball that deals 250 damage on contact

### Pharah

- Now falls much more quickly when the Crouch button is pressed

### Reaper

- Death Blossom now provides extreme gravity to Reaper while in use (off by default)
- Death Blossom now provides extreme jump force to Reaper while in use (off by default)

### Tracer

- Now passively heals for 25% of damage dealt (off by default)

### Ana

- Sleeping enemies now take 200% damage (off by default)

### Lúcio

- Sound Barrier now deals 2000 damage to anyone Lúcio lands on top of, within a small radius
- Sound Barrier now launches Lúcio directly upwards when it goes off
- Soundwave now gives Lúcio an upwards boost when pointed within 10 degrees of straight down

## Known Issues

- Sigma's shields do not regenerate past a certain point (fixable)
- Sigma's Experimental Barrier will not regenerate past 584 HP (no idea why this happens)
