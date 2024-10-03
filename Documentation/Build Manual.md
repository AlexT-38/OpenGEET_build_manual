# OpenGEET Build Manual

## General notes

The reactor will be installed vertically. Unprocessed fuel enters the reactor at the bottom and exits as Syn Gas at the top. Exhaust from the engine enters the reactor at the top and exits at the bottom.

Exhaust entering the reactor must be at the correct temperature and pressure. Temperature is controlled by setting the length of pipe work from the engine exhaust prot to the reactor exhaust inlet. Pressure is controlled by restricting flow at the reactor exhaust outlet.

Fuel entering the reactor must be a fine mist or dense vapour. For petrol/gasoline, the fuel to air ratio is around 1:5. The fuel/air mixture should be cool and at the correct vacuum, approx 0.5 atm.

A good vacuum seal for the reactor is vital. Leaks will at least cause lean running, at worst will prevent the reactor from operating.

The engine will run even if the reactor is not functioning. A running engine alone is not a sign of success.

Care must be taken to ensure gas flow paths are smooth and avoid sharp corners. Any rough surfaces, discontinuites and sharp corners will limit gas flow rates and reduce system performance. They may also cause unprocessed fuel to drop out of suspension and interfere with the reactor.

Magnetic alignment is important. The reactor must be assembled such that magnetic fields in the material align with the local geomagnetic field. Welds create strong magnetic fields in the material and can cause problems. Heat treating parts to above the Curie temperature and allowing them to cool in their installed orientations in an environment free of magnetic clutter may help.

Electrical conductivity is a concern. There must be a free path for electrons to flow through the reactor, feed pipe, gas mixer, engine and exhaust pipework back to the reactor. All parts in this loop should be made of metal. Any sealing compounds used should not insulate the joint. Specifically, PTFE tape should not be used on threads.

The design makes use of 12mm copper pipe. Unfortunately in the UK this is not a standard size and is only available from specialist plumping supply stores. It is available from BES.co.uk and for this reason, they are the prefered supplier for plumbing parts.

## Assembly overview

* Engine
* Reactor Assembly
    * Reaction Rod
    * Inner Tube
    * Outer Tube
    * Inner Tees
    * Outer Tees
    * Rod Support and Plug
    * Vacuum Monitor Ports
    * Sight Glass
* Intake Manifold Assembly
    * Manifold Adaptor and Vacuum Monitor Port
    * Gas Mixing Tee
    * Intake Valve
    * Intake Restrictor and Filter
    * Gas Delivery Pipe
* Exhaust Manifold Assembly
    * Manifold Adaptor
    * Connecting Pipe
    * Exhaust Inlet Pressure Monitor Port
* Exhaust Assembly
    * Muffler
    * Backpressure Adjustment Valve
    * Exhaust Outlet Pressure Monitor Port
* Fuel Delivery Assembly
    * Bubbler
    * Bubbler Feed Float
    * Bubbler Inlet Valve
    * Bubbler Inlet Restrictor
    * Fuel Feed Pipe

## Assembly Descriptions

#### Engine

A Honda GX120 or equivalent.

Remove the exaust, filter, carburetta and fuel tank.

#### Reactor Assembly

##### Outer Sub Assembly

Outer Tube is 3/4" x 150mm pipe with BSPT or NPT threaded ends. Remove the internal weld seam. Magnetic orientation of the tube is important, and should be aligned with the local geomagnetic field when installed.

Outer Tees are 3/4" malleable iron equal tees (plain, not nickel plated).

Outer Tees are fitted with 3/4"-1/2" reducer bushings with the inner thread bored out and honed. The bore must be cut after assmebly onto the tee, with the work centred on the tee's Outer Tube mating thread. This is the best we can do to ensure concentricity of the inner tube inside the outer tube. The face of the outer through port should be machined flat.

Outer Tees are fitted to the Outer Tube with the reducer bushings aligned.

All outer tube parts are assembled using red high temperature silicone RTV to seal the joints. Don't rely on tapered threads for sealing. Do not use PTFE thread sealing tape.

##### Inner Sub Assembly

Inner Tube is cold drawn seamless (CDS) mild steel tube, outer dia 17.5mm, wall 3.2mm, for an inner dia of 11.1mm, cut to a length of 317mm. The ends are given 3/8" BSPP threads and a 2.6x1.4mm (w/d) o-ring groove.

Red high temperature silicone orings, 14x2mm (ID/CS), are fitted to the inner tube's o-ring grooves.

The Inner Tube is passed through the Outer Tube and located by its o-rings inside the reducer bores. Again, magnetic orientation is important, and should be aligned with the local geomagnetic field when installed.

Inner Tees are 3/8" malleable iron tees (not nickel plated). Each port of the tee should be machined flat and square using the thread as reference. An o-ring groove should be machined into the face of each port. Currently a 19x0.75 counter bore on the outer and side ports, and a ~22x1.1mm face groove with a 7° taper on the inside wall for the inner port.

Inner Tube is clamped in place by the Inner Tees threaded against the Outer Tees.

All sealing should be performed by o-rings for the Inner Tube and Tees, but can be sealed with red silicone RTV if pressure/vacuum testing fails. O-rings at the top of the reactor must be of a high temperature type. Future revisions may use copper washers instead.

##### Reaction Rod

Reaction Rod is a length of mild steel, S275. Correct magnetic orentation is vital for this part.

The relationship between the outer diameter of the rod and the inner diameter of the Inner Tube controls the degree of vacuum in the reaction area and the maximum flow rate of fuel through the reactor.

The outer diameter should be tightly controlled and consistent over its length. The surface finish should be mirror like.

The length and nose profile are dependant on the fuel and installed orientation. Heavier grades of fuel require longer and blunter rods. European grades of petrol need a rod in the 90-95mm range, US gasoline is closer to 85mm.

The rear end of the rod is a shallow divet slightly smaller than the outer diameter. It can be cut with a standard drill, with loose tolerances on dimensions and surface finish.

##### Vacuum Monitor Ports

Ideally there should be two Vacuum Monitor Ports, one at each end of the reactor. These could be machined directly into the Inner Tees, or made from 3/8" BSP extenders. For now, only one port will be required, at the top of the reactor as an extension to the top most port.

##### Sight Glass

Sight Glass is connected to the top most port of the reactor. A more ideal set up for operation would be to have the syn gass delivery pipe connected directly to the top port, but we wwant to see what's going on at the top of the reactor.

When the reactor is operating, there should be a ball of plasma cupped in the divet on the tail end of the reaction rod. Spectographic analysis of the light from that plasma should give us great insight into the composition of syn gas. It's also a clear sign that the reactor is operating.

#### Intake Manifold Assembly

##### Manifold Adaptor and Vacuum Monitor Port

The GX120's intake port is D shaped. It has a plastic adaptor to transition to a circle, which doubles as a heat break to prevent the engine from heating the carburetta. This part must be replaced with an aluminum equivalent.

This is also as a place as any to place an intake vacuum sensor port. While not necessary, it will help in analysis and comparison with an unmodified engine.

##### Gas Mixing Tee

The Gas Mixing Tee mixes syn gas from the reactor with air drawn in through the Intake Valve. The Tee has a reduce bore and smooth transition so that it acts as a venturi pump, applying increasing vacuum to the syn gas feed pipe as the Intake Valve opens and admits more air. This helps maintain the correct operating vacuum in the reactor, since opening the intake valve would otherwise cause an increase in manifold air pressure.

The current design is machined from a block of brass and fitted with lengths of 12mm copper pipe, soft soldered into place. The restricted bore is 8mm in diameter (vs 10.1mm for the copper pipe).

##### Intake Valve

The Intake Valve is a standard 3/8" BSP full bore ball valve. For our purposes, the handle is removed and replaced with a 3D printed servo bracket.

While ball valves are not noted for their ability to fine control flow rates, they do a good job of sealing when closed and are readily available from plumming suppliers.

The Intake Valve is fitted with an Intake Restrictor and a 12mm compression fitting on the other, both with o-rings to ensure air-tightness.

##### Intake Restrictor and Filter

The Intake Restrictor is a brass 3/8" BSPP plug with a contoured hole.

The size and profile of the hole needs to be matched to the engine. The profile should be eliptical on the outside and conic on the inside. This profile offers optimal flow rates over a range of vacuum levels. This is important for single cylinder engines as the intake flow is discontinuous. Increasing the range of flow rates over which vacuum can be maintained increases the range in which the reactor is operating, and improves performance.

Filtering is optional, but will reduce engine wear from ingested particulates.

#### Exhaust Manifold

##### Manifold Adaptor

##### Connecting Pipe

##### Exhaust Inlet Pressure Monitor Port

#### Exhaust Assembly

##### Muffler

##### Backpressure Adjustment Valve

##### Exhaust Outlet Pressure Monitor Port

#### Fuel Delivery Assembly

##### Bubbler

##### Bubbler Feed Float

##### Bubbler Inlet Valve

##### Bubbler Inlet Restrictor

##### Fuel Feed Pipe