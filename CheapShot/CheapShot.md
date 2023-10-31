The CheapShot is my attempt to build a simple shooter with an adjustable hood. The design is parametric but for ease of prototyping I sized it to shoot wiffle-balls, similar to those used in a previous FRC game. It also has a base that can mount directly on the [CheapTurret](/CheapTurret/CheapTurret.md).

Since a larger ball size can easily result in parts that are too large for typical 3D printers, the large parts of the shooter are flat-pack tab-in-slot components that can be manufactured on a basic CNC router.

[![CheapShot Demo](https://markdown-videos-api.jorgenkh.no/url?url=https%3A%2F%2Fyoutu.be%2FPwDe70TSEHk)](https://youtu.be/PwDe70TSEHk)

Finally, one of our students was playing around floating a ball a jet of air, and that got me wondering if an air-conveyor could be used to feed balls into the shooter (as opposed to using the typical belts). And the answer is -- yes, yes it can. And it's pretty hilarious.

[Blowups Happen Demo](https://youtube.com/shorts/p--w9OTOHpk?feature=share)

# Notes

* No detailed build description; it should be fairly obvious how things go together. Almost everything is assembled using rivets -- turns out rivets work really well with 3D-printed parts.

* Fusion 360 Projects are [here](Files/). Included are the CheapShot, a 775-powered centrifugal blower, and some pipe components for the air-conveyor.

* The brackets used to assemble all the flat-pack panels are [Everbilt 2" Inside Corner Braces](https://www.homedepot.com/p/Everbilt-2-in-Zinc-Plated-Inside-Corner-Brace-12-Pack-12634/315016361) which are available at Home Depot. You have to drill out the holes to accept the rivets.

* The linear actuator for the hood is an [AndyMark AM-3515](https://www.andymark.com/products/actuator-l16-r-50mm-stroke-35-1-6v?sku=am-3515); you can also use a regular servo such as an HS-422 if you prefer, but the range of motion may not be as large.

* The shooter can be powered by one or two NEOs. For each, you'll need a [REV-21-1879 hex shaft adapter](https://www.revrobotics.com/rev-21-1879/) and two 9mm HTD pulleys (such as the [WCP-0604/0563](https://wcproducts.com/products/htd-timing-pulleys)).

* The shooter wheels are mounted using [Versaframe 217-4813 plates](https://www.vexrobotics.com/versaframegussetsandmounts.html), Thunderhex bearings, and some shaft collars to secure the shaft and the wheels. I just ended up putting a shaft collar between the two wheels as a spacer.

* There's an integrated mount for a Limelight 2 or 3.
