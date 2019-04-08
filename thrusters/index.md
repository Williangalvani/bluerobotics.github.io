---
layout: default
title: T100 Thruster Documentation
permalink: /thrusters/
order: 0
nav:
- Safety: safety
- Important Notes: important-notes
- Installation: installation
- - Changing the Propeller: changing-the-propeller
- - Mounting Options: mounting-options
- - Electrical Connections: electrical-connections
- - How to Cut and Strip the Cable: how-to-cut-and-strip-the-cable
- Operation: operation
- - Clicking Noise: clicking-noise
- Care and Maintenance: care-and-maintenance
- - Normal Care: normal-care
- - Disassembly/Assembly: disassemblyassembly
- Troubleshooting: troubleshooting
- Details: details
- - Test Results: test-results
- - Quality Control: quality-control
- - Painting the Thruster: painting-the-thruster

store-links:
- T100 Thruster: http://bluerobotics.com/store/thrusters/t100-thruster/
- T200 Thruster: http://bluerobotics.com/store/thrusters/t200-thruster/

manual-links:
- T200 Thruster: /thrusters/t200/
- M100 Motor: /thrusters/motors/
- Basic ESC: /besc/


tutorial-links:
- Thruster Assembly/Disassembly: /tutorials/disassembly-assembly/
- Changing the Propeller: /tutorials/changing-the-propeller/
- Cable Stripping: /tutorials/cable-stripping/

redirect: https://www.bluerobotics.com/store/thrusters/t100-t200-thrusters/t100-thruster/
---
<img src="/assets/images/documentation/2-t100s.png" class="img-responsive img-center" />

# Safety

Always practice caution when you're working with electricity in water and with the spinning blades of the propeller. Keep body parts away from the thruster inlet and outlet to avoid injury.

# Important Notes

<i class="fa fa-exclamation-triangle fa-fw fa-2x text-warning"></i>
Do not operate the thruster for extended periods (more than a few seconds) out of water. The bearings are lubricated by the water and vibration and noise will be greater when dry.

<i class="fa fa-exclamation-triangle fa-fw fa-2x text-warning"></i>
Do not operate the thruster for extended periods (more than a minute) at full throttle in water. If not allowed to cool periodically, damage can occur. We recommend our T200 thruster for long period high throttle use cases.

<i class="fa fa-exclamation-triangle fa-fw fa-2x text-warning"></i>
The thruster can handle saltwater and sandy environments pretty well, but it does not get along with seaweed. Avoid sucking seaweed into the thruster to avoid damage.

<i class="fa fa-exclamation-triangle fa-fw fa-2x text-warning"></i> Most threadlockers are not chemically compatible with with polycarbonate, and will damage the thrusters if used on any of the screws. Refer to the documentation and chemical compatibility notes of your threadlocker of choice for more information.

<i class="fa fa-lightbulb-o fa-fw fa-2x blue"></i>
A slight clicking noise is normal, especially when operated dry. It is caused by slight movement of the shaft in the plastic bearings.

# Installation

The T100 Thruster is easy to install in many different applications. It was designed with versatile mounting options for a variety of different applications. It includes a counter-rotating set of propellers. Check out the tutorial on how to change the propeller. 

## Changing the Propeller
<div class="row">
  <div class="col-sm-4 col-md-4">
  	<div class="tile" style="background-image:url(/assets/images/tutorials/changing-a-propeller/propeller-3.png)">
  		<a href="/tutorials/changing-the-propeller/">Changing the Propeller <i class="fa fa-chevron-circle-right"></i></a>
  	</div>
  </div>
</div>



## Mounting Options

The T100 Thruster has several mounting options. The nozzle has four mounting holes that can be used to secure directly to vehicle. 

Occasionally, these holes may not be convenient or it may be difficult to secure the screws. In this case, the mounting bracket may be a better option. The mounting bracket is secured to the thruster through the four screw holes. It can be mounted in two different orientations as shown below.

<img src="/assets/images/bracket-1.png" class="img-responsive" style="max-width:500px" />

*Thruster with bracket in front/back orientation*

<img src="/assets/images/bracket-2.png" class="img-responsive" style="max-width:500px" />

*Thruster with bracket in side to side orientation*

The mounting bracket also includes a guide hole that can be drilled out with a 1/4" (6.5mm) drill bit to allow the wire to pass directly through the bracket.

Which mounting option you choose depends on your application.

## Electrical Connections

### Connecting to an External ESC

The thruster has a cable containing three wires. These three wires must be connected to the three motor wires on the electronic speed controller (ESC). The order does not matter, but if the motor direction is the reverse of what is desired, switch two of the wires. 

The three wires in the cable (green, white, blue) are always connected to the same motor phases, so connecting the colors in a consistent fashion will result in all motors rotating in the same direction.

## How to Cut and Strip the Cable

The thruster comes with a tough urethane-jacketed cable. This is great for use underwater, but it can be a little difficult to remove the jacket from the wires if you want to cut the cable to a shorter length. During production, we use a thermal wire strippers, but the jacket can also be removed with a razor blade or hobby knife. Check out the cable stripping tutorial with pictures here:

<div class="row">
  <div class="col-sm-4 col-md-4">
  	<div class="tile" style="background-image:url(/assets/images/tutorials/wire-stripping/wire-strip-7.png)">
  		<a href="/tutorials/cable-stripping/">Cable Jacket Stripping <i class="fa fa-chevron-circle-right"></i></a>
  	</div>
  </div>
</div>

# Operation

The thruster requires a brushless electronic speed controller (ESC). Check out our Basic ESC page for more information.

<div class="row">
  <div class="col-sm-4 col-md-4">
  	<div class="tile" style="background-image:url(/assets/images/documentation/besc-3-new.png)">
  		<a href="/besc/">Basic ESC <i class="fa fa-chevron-circle-right"></i></a>
  	</div>
 </div>
</div>



**Important:**
Do not operate the thruster for extended periods out of water. The bearings are lubricated by the water and vibration and noise will be greater when dry.

## Clicking Noise

If you hear a clicking noise during operation, especially when operating in air, do not be alarmed. It's normal.

The thruster uses solid plastic bushings and due to the tolerances of the bushings and motors shafts, the shaft can move slightly in the bearing. The noise is drastically reduced or eliminated when operated in water. The water acts as a lubricant for the bearings and smooths operation.

# Care and Maintenance

The T100 Thruster does not require much maintenance.

## Normal Care

During normal use:

* Rinse with fresh water after use in saltwater to minimize the accumulation of salt deposits.

* Rinse after operating in sandy environments to remove sand particles.

If operated for extended periods in the water:

* Occasionally clean biological fouling and mineral deposits from the thruster or performance may be impacted.

## Disassembly/Assembly

You may need to take apart your thruster from time to time - or maybe you just want to take a peek at the inner workings of the T100! Either way, this tutorial illustrates how.

<div class="row">
  <div class="col-sm-4 col-md-4">
  	<div class="tile" style="background-image:url(/assets/images/tutorials/disassembly/disassembly-2.png)">
  		<a href="/tutorials/disassembly-assembly/">Disassembly/Assembly <i class="fa fa-chevron-circle-right"></i></a>
  	</div>
  </div>
</div>

# Troubleshooting

**The motor does not start.**

This is usually an issue with the proper commands being sent to the ESC. Please see the [ESC documentation](/besc/) for instructions on how to operate the ESC properly.

**The motor does not start but the propeller tries to move.**

This can be caused by a disconnected motor wire or a short between motor wires. Check that all three motor wires are connected and not shorting. To do this, check resistance of each phase pair in the thruster. Each thruster wire phases pair (Blue/green. blue/white, green/white) should have the same resistance within 0.1-0.2ohms or so. If no connection is read or one pair has significantly higher resistance, your thruster has a fault. Please e-mail [support@bluerobotics.com](mailto:support@bluerobotics.com) if this fault is found.

**The motor is jammed when turned by hand.**

This can be caused by something jamming the propeller or by major internal damaged caused by overheating, short circuits, or heavily worn bearings. Please disassemble the thruster and inspect for damage or blockage.

# Details

For all the engineers out there, here's some more info.

## Test Results

* **Endurance Testing.** [The T100 has been tested for over 2400 hours](https://youtu.be/HBtxAO1sL7k) in virtually continuous operation at half throttle, only being halted shortly for internal inspection every few weeks. 

* **Sand and Particulate Testing.** The thrusters handle small particulate matter very well. See [this video](https://www.youtube.com/watch?v=0X0EncNR8l8) of testing the thrusters in heavy sand.

* **Depth Testing.** As of writing, the thrusters have been tested to a maximum depth of 3000m (4500 psi) in static conditions. This testing was performed by Woods Holes Oceanographic Institution and you can [read more about it here](http://www.bluerobotics.com/pressure-testing-3000m-depth/).

## Quality Control

We perform the following tests on every thruster before they are shipped.

* **Insulation Test**, also know as a hipot test. We submerge the thruster in water and measure current leakage at high voltage (250V) to ensure that the insulation is sufficient.

* **Spin Test**. The thruster is operated in air across the entire speed range to ensure that it operates correctly.

* **Visual Inspection**. Each thruster is inspected for visual issues or damage.

## Painting the Thruster

If you want the thruster to match the color scheme of your vehicle, you can paint the propeller and other components. We have tested [Tamiya Spray Paint for Polycarbonate](http://www.tamiyausa.com/items/paints-amp-finishes-60/spray-ps-(polycarbonate)-61700) which comes in many colors and works well on the plastic.
