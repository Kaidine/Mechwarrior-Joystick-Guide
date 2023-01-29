# Mechwarrior Joystick Guide

## Overview

### Summary 
This guide should walk you through getting joysticks (or other HID devices) working with MechWarrior titles both past 
and present. As of right now, this will only work on *native Windows* systems. I'd love to include support for 
Mac/Linux, but the programs I'll be describing here are Windows-only. Alternatives may exist, but I'm not aware of them-
If you know of any, let me know or open a pull request!

This guide is entirely based off of what worked for me; It should work for any Windows pc and joysticks, but I can't 
guarantee (or test!) it. Even if it doesn't work exactly the same way for you, I hope it will be a good jumping-off 
point to 'Mech-blasting fun!

Oh, and the usual disclaimers: I don't own any MechWarrior or BattleTech IP. I don't work for any of the companies that 
have made these games, either now or in the past. I'm not even a mod author for any of them. I'm just a nerd who wanted 
to pilot some big stompy robots, and to use a joystick to do so. Share this guide with whoever, for whatever reason; 
Make any edits you want (albeit not in this repository, please...). I just hope this eases your way into playing the 
MechWarrior series with joysticks! 

### My Setup

For context, this is the hardware that my setup is currently running on (mostly which joysticks). This shouldn't make 
much difference outside of specific key bindings, but I've included it nonetheless.

 OS: Windows 10 (I have *not* tried this on Windows 11)

 PC: 6th gen Intel i7, Nvidia GeForce Gtx 1080

 Joysticks:
 - VKB Gladiator NXT EVo "Space combat Edition" (premium right-handed grip)
 - ThrustMaster TWCS throttle
 - VKB T-Rudder Mk.IV rudder pedals
 

## General Instruction Outline

Instructions specific to each game will be added in the respective subfolders as I write them. All instructions will 
assume that you have a working copy of the game installed - installing the game is *not* part of this guide, although I 
will provide links to guides I used where I can. 

Generally speaking, setting up joystick support will look like the following:

1. Download and install vJoy and joystick gremlin, if you don't already have them.
   1. vJoy can be found [here.](https://sourceforge.net/projects/vjoystick/)
   2. Joystick Gremlin can be found [here.](http://whitemagic.github.io/JoystickGremlin/)
2. Configure a vJoy device to have an appropriate number of axes and hat switches. It may help to create a different 
virtual device for each game. Buttons are optional, but not necessary.
3. Create a joystick gremlin profile. I recommend a different profile for each game!
4. In that joystick gremlin profile, map the desired axes of your physical joysticks/gamepads/buttonboxes to an axis of 
the virtual device. If you're using a different virtual device for each game, make sure all the mappings are to the 
*same* virtual device! 
   1. Generally, due to the limitations that some games place on number of joystick buttons available, it's best to map 
   individual (physical) buttons to virtual keyboard keys. This also allows you to do keybindings entirely outside of 
   the game itself - map whatever physical button you like to the default key binding of the game, and you're golden!
5. Configure the game to use the *virtual* joystick (and keyboard) as input.
   1. This is one of the tricky parts - defer to the game-specific instructions for this one!  
6. When you want to run the game, activate the appropriate joystick gremlin profile.
7. Collect Salvage! ; )
