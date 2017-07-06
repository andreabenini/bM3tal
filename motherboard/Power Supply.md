# bM3tal Power Supply
I had a spare 24V 10A Power Supply and I wanted to use that one, even if it's a switching PSU seems to be a tough and reliable voltage source, but, unfortunately my Arduino Shield and a lot of things here are working on 12v. I have ditched it for a more common PC power supply, absolutely less efficient and cheap but seems to be powerful enough to keep things going.<br/>
Rated values for this power supply are +12V/15A, +5V/17A for an overall 350W usage. After "classic" mods for using it outside a PC I'll see how it goes with it, it's not an additional cost because I already have it lying around, I'll test it to see how it performs.

## PC Power Supply Mod
In PowerSupplyPinout.png file there's the main connector pinout as a reference for a classic mod as seen [here](http://makezine.com/projects/computer-power-supply-to-bench-power-supply-adapter/). I haven't cut the PSU cables so I have decided to create a connector adapter between the PSU and the Arduino Shield. This power supply provides GND,5V,12V, other voltages aren't needed at all
