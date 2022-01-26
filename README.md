# Overwatch EmuPatch

A custom patch for Overwatch with several toggleable changes to hero abilities, meant for both balance and entertainment. Please note that this is still in development and will likely have plenty of bugs and strange interactions even as time goes on, simply due to its nature as a workshop script.

## Usage

This code is written in [Deltin's OSTW language](https://github.com/ItsDeltin/Overwatch-Script-To-Workshop), so it has to be compiled with the associated VS Code extension before use. Alternatively, you can find the most recent version already compiled [here](https://pastebin.com/raw/492p6RSx). Simply copy all of the text on the page to your clipboard, and click the button shown below in Overwatch to load the gamemode and workshop settings.

![Overwatch Paste Workshop Code Button](https://user-images.githubusercontent.com/23511921/148482375-516ad5d2-0c0b-46c8-a3c9-650392a293c5.png)

Once this project reaches an acceptable level of features, I will generate a proper code for it and update that instead. For now, the above method is easiest.

## Changes

All of the changes listed below can be toggled through the workshop settings to fit your preferences.

### Orisa

- Can now be mounted like a horse with the Interact key, and dismounted with the Crouch key (off by default)

### Reinhardt

- Charge can now be ended early by pressing the Charge key a second time
- Reinhardt will now always be full throttling forwards, regardless of user input (off by default)

### Winston

- Primal Rage max health increased from 1000 to 1500

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
