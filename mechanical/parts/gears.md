---
title: Gears
---

## Spur Gears

Spur Gears are the most commonly used gears in FRC. The individual teeth have a straight cut involute profile. Mating (or meshing) gears must have the same specific number of teeth per unit of circumference and pressure angle.

US System gears are specified in Diametral Pitch (teeth per inch of diameter), and pressure angle. Metal Gears are typically available in a DPs of 3 to 32, and pressure angles of 14.5⁰ & 20⁰. Plastic Gears and Brass gears typically run with a DP of 16 to 64 and a pressure angle 20⁰. The normal gears sold by AndyMark and Vex have a DP of 20 and a Pressure Angle of 14.5⁰.

The Pitch Diameter is the location where the teeth mate:

PD = Number of teeth / Diametral Pitch

The Outside Diameter of the gear is:

OD = (Number of teeth + 2) / Diametral Pitch

Metric Gears are specified by module with is simply the Pitch Diameter/number of teeth. They all use a 20° pressure angle. The only metric gearing commonly used is some of the FRC legal automotive window & throttle motors. The metric module 1.25 gearing is the most similar to the 20DP gearing. Module 1.0 gearing is equivalent to a 25.4 DP.

### Planetary Gearboxes

Another use of spur gears is a planetary gear set ("epicyclic gearing"). The central gear is the sun gear. The Planetary gears are normally attached to a carrier that rotates with center of the planet gears. The Ring Gear is normally static, but can be rotated as well depending on the design needs. There are a number of FRC gearboxes available from AndyMark, Banebot, and Vex that use planetary gears. In these the Ring Gear is fixed to the case, and the sun gear is used to drive the planet gear carrier of the next stage or the output shaft. The total reduction in this situation is R=1 +(Ring Gear Teeth)/(Sun Gear Teeth). By using several subsequent (stacked) planetary sets, it’s possible to achieve 150:1 or more reduction ratios in a small gearbox.

As an example, the extremely popular VersaPlanetary has uses a 72 tooth ring gear. The 5:1 ratio kit has a sun gear with 18 teeth, and four planet gears with 27 teeth. Note that the sun and two planet gears add to 72 as well. The reduction ratio =1+72/18=5 as expected.


## Bevel & Miter Gears

Bevel gears are used to change the rotation angle 90⁰, and can also provide a speed reduction or increase depending on the tooth counts. Miter gears are simply bevel gears with the same tooth count (1:1 ratio). Bevel gears are normally bought as a set. The teeth are cut so that both angles meet at a central point, making each profile cone like. Bevel gears apply force away from each other in use, and should always be used with a thrust bearing on the backside.


## Worm Gearing

Worm Gears are another method of turning the rotation angle 90⁰, and can provide a very compact speed reduction (up to 75:1). These are also always purchased as a set of gears. The worm is normally of steel construction, and the worm gear is normally a softer metal such as brass to control wear. One special property is that the worm gear can’t back-drive the worm, which can be a helpful property is some applications. For example, almost all stringed instruments use worm gears in their tuning pegs where both the mechanical advantage and the lack of back-drive is very useful.


## Other Gearing

There are other forms of gearing available including multi-angled herringbone gears, slanted helical gears and curved gearing such as hypoid, and cycloid. These are typically more expensive, more difficult to source, and challenging to design with. There is probably very little need for these on an FRC robot.


## Gearing Efficiency

Each stage of gearing will result in some inefficiency in the power transmission. Worm gear efficiency is a function of the lead angle of the worm. Lead angles of 45⁰ provide the maximum efficiency.

| Type            | Normal Ratios   | Efficiency      |
|-----------------|-----------------|-----------------|
| Spur            | 1:1 to 6:1      | 94% to 98%      |
| Straight Bevels | 1.1 to 5:1      | 93% to 97%      |
| Worm Gearing    | 5:1 to 75:1     | 90% to 95%      |