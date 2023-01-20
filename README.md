# ender3-corexy

# Ender 3 (Pro, V2) CoreXY conversion using MGN9H Linear Rails

This design is licensed under CC-BY-NC-SA 4.0 (see LICENSE.TXT).

The GitHub repo currently lags the Onshape model until I push an update every so often, but the design is openly available on Onshape:

[https://cad.onshape.com/documents/7dfd800c94b330690f19f3b3/w/606c674af3b9bda8b15e0a0f/e/0d280d52ccda5ae23c93c658](https://cad.onshape.com/documents/7dfd800c94b330690f19f3b3/w/606c674af3b9bda8b15e0a0f/e/0d280d52ccda5ae23c93c658)

## Goals / Principles

The goal is an 80-20/bang-for-buck type conversion, ideally putting the money where it hopefully matters most. I've seen some other conversions using linear motion rods outside the frame but I prefer linear rails and within the frame, even though those mods re-use more parts of the original Ender.

Some of the goals:
- Solid, hopefully reliable mid-range, mid-speed machine - have it printing very well at around 100mm/s,
- MGN9H linear rails on X and Y and a mix of MGN9H linear and zruncho-style printed rails for Z,
- designed around a kinematic triple-Z with klicky-style probing as that's my preferred setup right now but other Z designs should be mostly drop-in,
- keep the printed parts simple-ish, easy-ish to print and keep parts and BOM count down if possible,
- wanted to try some risky design-decision and see if they work out, like floating rails (🫢), zruncho-style Z.

A rough estimate of the conversion using Amazon-US prices for everything I could think of (including 8-driver board capable of running Klipper, TD6S hotend, BMG gears, ...) puts it around $350 + price of Ender 3 (~$89-109 for a "returns/used/parts" printer at Comgrow for example), can be lowered by compromising on certain things.

## Ender 3 Parts currently re-used

Re-uses the base of the frame as a super rigid foundation and the upright 2040s, power supply, motors, lead screw would need to be cut:

![Ender 3 CoreXY with](https://github.com/thingsapart/ender3-corexy/blob/main/images/Ender%203%20CoreXY%20Base.jpg?raw=true)

The plan is also to make a version of the Z-assembly re-using the Ender 3's V-Rollers.

## Toolhead

A couple toolhead variants are planned, especially one variant using the standard Creality hotend mount.

Currently supports Voron V0-style Toolheads to get this off the ground like the Mini-Afterburner, Mini-Stealthburnder, Mini-AfterSherpa, V0VO, DragonBurner and Mailbox, Mini-B.

![Ender 3 CoreXY with toolhead](https://github.com/thingsapart/ender3-corexy/blob/main/images/Ender%20CoreXY%20Voron%20Toolhead.jpg?raw=true)
