# Useful Parts

These are some minor parts that you may find useful in your projects. The Fusion360 projects are included so you can modify them as needed, and are usually parametric.

# Parts complicated enough to require some explanation

* The [CheapHook](CheapHook/CheapHook.md) converts a common U-bolt into a hook that attaches to the end of a 1" square tube.

# Parts simple enough to (hopefully) require no explanation

* [REV-21-2120 CANCoder Holder](SensorMounts). A small mount for attaching a CANCoder to a REV right-angle gearbox. Can be adapted for similar uses.

* [Sensor Mounts for 2" Tube](SensorMounts). Combine one of the specialized holders (Hall Effect or IR sensor) with a Basic Tube Mount and a couple of bolts and you can securely clamp your sensor to 2" square tube.

* [Cable Chain](CableChain). Comes in two variants, a basic cable-chain link and an axis-shift variant that lets you change the plane in which the chain is bending (this latter requires support to print). You have to thread your wires through the chain links (they don't snap open) but this tradeoff means they are easier to print and assemble. I use them in the [CheapTurret](/CheapTurret/CheapTurret.md) Project.

* [2-inch Square Bolt Spacer](Misc). A little part that slides onto a 2-inch square u-bolt and lets it clamp flatly on 2-inch square tubing.

* [Round Belt Pulley](Misc). A small pulley that slides onto 1/2-inch hex tubing and has a groove for round belts. Parametric so you can resize it.

* [2-Part Thunderhex Bearing Mount](Misc). A simple bearing mount that clamps a Thunderhex flanged bearing in place. Particularly handy for prototyping on T-slot.

* [Bolt Thumbscrew Wide-Flat](Misc). Print these out, press in a 1/4-20 hex bolt, and you've got a nice thumbscrew. Has sacrificial support built in, just push the bolt through it from the "wrong" side to break it off, clean up with a deburring tool, and then insert the bolt properly.

* [Hex Magnet Holder](Misc). A little hex nubbin for mounting a CANCoder magnet to hex shaft. Push the magnet in one end, and screw the other end onto the end of some threaded hex shaft with a cut-off bolt or set-screw. You can adjust the set-screw so that it touches the back of the magnet and holds it at the desired distance from the sensor. Once it's all in place, add a dot of glue to the tip of the magnet to hold it in place. It's a lot easier than mounting the magnet directly into the hex shaft.

* [Radio Mount](Misc). Yet another mount for the FRC radio, this one lets the radio drop into the mount. Lots of ways to secure it once it's in, but a zip-tie at the top is the easiest. Releases in seconds when you need to get the radio flashed at a competition. All the cables come out the bottom.

* [Parametric Hinge](Misc). A simple parametric print-in-one-piece parametric hinge. You get to specify length, width, size and # of mounting holes and more.

# Building Blocks

* The [HTD Flanged Pulley](Misc) is a Fusion 360 project that helps design and build HTD belt pulleys. It is fully parametric and lets you specify things like belt type, number of teeth, flange size, bolt circle, and whether or not the hex shaft has a raised hub. Due to limitations in Fusion, depending on what features you want you will have to do some timeline editing, mostly feature suppression toggling. Stepping through the timeline should make things fairly obvious. This project is an extension of Robert K's [Parametric HTD Pulleys](https://grabcad.com/library/parametric-htd-pulleys-1).

  Some notes:

  * All the parameters have comments that are hopefully helpful.
  * If you have a raised hub, the slope of the flange is limited to about 60 degrees if you want to print without support; otherwise it should be set to 80 degrees.
  * You will have to change the hole feature to alter your bolt holes. Usually you will be printing two half pulleys that differ in their bolt holes (for example, countersunk bolts on one half, threaded holes in the other). There is also a feature to expand a countersink so flathead bolts nest flush with the pulley surface (printing limitations often cause them to be a little proud if you don't add some tolerance).

# Jigs and Guides

* [Belt Welding Jig](Misc). A small jig that can hold some round tubing in place. Print two of them, slide onto a length of T-slot, and you'll be able to heat the ends of the tubing and then push them together reasonably precisely.

# Brackets (aka Gussets)

* [Some simple brackets](Brackets) that fill in the gaps of the standard brackets you can get from AndyMark and Rev, with DXF files suitable for use with a CNC router. You will probably need to scale the DXFs by 25.4 after importing them because last time I checked, Fusion doesn't include the scale information in the DXF, despite that being possible. The Custom Short L-Bracket is particularly handy because you can use 4 of them to wrap around a 4-way intersection in your frame and attach a vertical strut.