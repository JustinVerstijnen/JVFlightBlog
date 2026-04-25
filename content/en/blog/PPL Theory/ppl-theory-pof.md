---
title: 'Principles of Flight (POF)'
date: 2025-07-08
slug: "ppl-theory-pof"
categories:
  - PPL Theory
tags:
- AI Generated Content
description: >
  This page contains my notes for the Principles of Flight (POF) exam. This contains various subjects like lift, aircraft performance and why an aircraft flies.
---

{{% alert title="Disclaimer" %}} For a live overview of my flight lessons, visit: <https://flighttools.justinverstijnen.nl/flightlessontracker>

This page can contain a collection of personal notes, steps to remember, finished and unfinished content. Please excuse brevity.

Do not use specific information given like fuel flow, landing/take-off distances for your flights. Always refer to the POH of your exact plane for flight preparation. My information is just for references that I used. {{% /alert %}}

---

## The atmosphere (1)

The atmosphere is the layer around the earth, which is around 100 to 200km from the ground up. Worldwide, we use the International Standard Atmosphere which is a mean set of conditions which will be somewhat different depending on the weather conditions, location etc. This is a mean of the conditions at 45 degrees north latitude.

In the standard atmosphere, we use these characteristics:

1. 0ft is at the mean sea level
2. The air density is 1,225 kilograms per cubical meter
3. The air pressure is 1013,25 hPa (millibar) or 29.92 inches of mercury (inHg)
4. The temperature at sea level is 15 degrees celsius
5. In the troposphere, the temperature decreases with 2 degrees celsius for every 1000ft up (2 degrees per 300 meters)
6. The tropopause is at 36.000ft (11km) and the temperature is -56,5 degrees celsius
7. The troposphere and stratosphere contains 78% carbon dioxide (co2) and 21% oxygen

This is a set of conditions, but some numbers can defer in the real world, due to the location or different seasons. Now, lets take a look at the different layers in our atmosphere:

|  |  |  |  |
| --- | --- | --- | --- |
| **Layer** | **Altitude** | **Characterstics** | **Temperature** **gradient** **(ISA)** |
| Thermosphere | 280.000ft and up 85km and up | Thin air and high temperature due to solar radiation. Auroras happen in this layer | Increases with altitude |
| Mesosphere | 160.000ft - 280.000ft 50km - 85km | Meteors burn up in this layer, coldest layer | 0c to -90c |
| Stratosphere | 36.000ft - 160.000ft 11km - 50km | Contains the ozone layer, stable air with some jet streams at the bottom | -56,5c to 0c |
| Troposphere | 0 - 36.000ft 0 - 11km | Bottom layer at the ground of earth and where weather/clouds take place | 15c to -56,5c |

This is a repeat of the information already learned in the Meteorology course. For more information, [check out](https://flightblog.justinverstijnen.nl/ppl-theory-met/#the-atmosphere-1)

### Air Pressure

Air pressure is a result of the mass/weight of the air. Because there is so much air above the earth which compresses close to the ground, areas with a lot of air molecues will be created. You can see this as a tower of jenga you played before. The weight of all the bricks pushes on the lower layers of bricks.

On earth we have several high pressure areas and low pressure areas which are an result of temperature differences. High pressure areas always wants to go to low pressure areas, just like when you pump up a tire and let go the vent. The air from the high pressure area inside the tyre will go to the outside, low pressure area.

- In high pressure areas: cold air falls to earths surface, and cold air has more air molecules
- In low pressure areas: warm air from the surface rises, and warm air has less air molecules

So air pressure actually indicates the volume of air molecules in the area. The higher the pressure, the higher the volume of air molecules.

High pressure (H) and low pressure (L) areas are not absolute numbers, but relative to each other. For example:

- 979hPa (L) vs. 1013hPa (H)
- 1013hPa (L) vs. 1035hPa (H)

### Air Pressure when elevating

When going up into the air, the air pressure will decrease like seen in the graphic below:

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-met-5661/jv-media-5661-f5f05dfafc9e.png)

For reference, we will use this numbers:

- Every 30 feet up in the air represents an hPa loss in air pressure
  - Example: 1013 hPa on sea level (0ft AMSL) means a mean pressure of 1000 hPa at 390ft altitude

As this is an exponential relationship, this will guide you through the first 10.000ft (3,048km) in altitude, after that this trick does not longer work correctly of course. Some good rules of thumb:

- 5.000ft altitude: 75% (3/4) from ground pressure
- 18.000ft altitude: 50% (2/4) from ground pressure
- 34.000ft altitude: 25% (1/4) from ground pressure

For more information about Pressure and Density altitude, check out: [https://flightblog.justinverstijnen.nl/ppl-theory-nav/]( https://flightblog.justinverstijnen.nl/ppl-theory-nav/)

### Pressure Altitude

Pressure altitude is the altitude corrected to the International Standard Atmosphere, namely 1013 hPa (which is also called QNE). For performing take-off calculations, we will want to know how our plane performs which can be different with different pressures. This is a live indicator of being above or below earth's standard atmosphere.

In short:

- Higher pressures (Low altitiudes): Better engine performance, better propellor performance and more lift
  - More oxygen and more air molecules
- Lower pressures (High altitudes): Less engine performance, less propellor performance and less lift

### Pressure altitude examples

In an airport which mostly is lower or higher than mean sea level, there will be a small correction needed. For example, our airport is at 17 feet above sea level, and the actual pressure is 1032 hPa on sea level at a day with nice weather, the pressure altitude is -489 ft. This means our take-off performance will be better as we have more air molecules which is better for our engine.

In the same example with a pressure of 968 hPa on sea level, we will have a pressure altitude of 1238ft. This means our aircraft will perform as it takes off at 1238ft above sea level, which will have some disadvantages. As there is less air, we will need a longer runway, our engine performance is less and our lift will be less as there is less air. However, flying in relative high pressure altitudes is good for having speed, as drag decreases in lower pressure.

As you can already see, this example gives two completely different scenario's with around 1700ft difference. In countries like the USA where airstrips can be at 5000ft altitude, the pressure can be a huge difference which we must take into account.

Check out this tool to calculate and visiualize Pressure/Density altitude: <https://flighttools.justinverstijnen.nl/pressuredensityaltitudecalculator>

### Density altitude

Now we know the pressure altitude, we need to correct it for Density altitude, because warmer air is thinner than colder air. This is because warmer air expands, just take a look at a hot air balloon. This means that on 5000ft pressure altitude and on a hot day of 35 degrees, the density altitude (also known as "performance altitude") will be almost 9000ft. So we can expect our plane to behave as it is on 9000ft in normal ISA conditions.

Thinner air means less oxygen and less air molecules, denser air means more air for lift for both propellor and the wings. Less oxygen also means less engine performance but a higher true airspeed due of less resistance from air molecules.

To calculate the density altitude from pressure altude, you can use the E6B or the tool below:

Check out this tool to calculate and visiualize Pressure/Density altitude: <https://flighttools.justinverstijnen.nl/pressuredensityaltitudecalculator>

> Tip: Use an E6B calculator for a quick and thorough calculation of Density altitude based on the outside air temperature (OAT) and pressure altitude.

---

## Lift (2)

Lift (draagkracht in Dutch) is a component that keeps a plane in the air. This is the upward force that fights the gravity/weight of the plane. It works basically as the wind flows over and under the wing. As the air over the wing goes faster and under goes slower, it will combine at the end of the wing. We can explain why an aircraft flies because of 2 elementary laws:

| Law | Definition |
| --- | --- |
| The continuity law | A conserved quantity cannot disappear or appear spontaneously; it can only move from one place to another.In fluid flow, this means the amount of mass entering a system must equal the amount leaving it, as long as nothing is added or removed inside. That is why a fluid flows faster when it passes through a narrower section. |
| Bernoulli's law | In a flowing fluid, an increase in speed is accompanied by a decrease in pressure, provided the flow is steady and friction losses are negligible.Bernoulli’s law explains how that increase in speed is related to a decrease in pressure. Compare this to pinching a garden hose. |

Both laws describe that a flow in a narrow area will go faster and has a lower pressure. This helps us better understand how an aircraft flies.

### How an airplane generates lift

Lift works basically with these 4 components:

- **Wind velocity:** The more headwind (speed) you have, the more air and air molecules will hit your wing. This pushes the wing upward where the wind will then be directed to the ground and changes the velocity. Changing the direction and velocity of this wind has a reaction which is lift force.
- **Angle of Attack:** The angle of attack is the angle of the wing hitting the wind. By default, planes have a little angle of attack of a few degrees but we can increase this with the yoke (steer) of the plane
- **Drag:** The drag component is how much air resistance we have in a particular situation. The higher the angle of attack, the more drag and how harder the engine must work to compensate for it, which can evantually result in a stall
- **Lift force:** The lift force is the resultant of the wind velocity, drag and the angle of attack and states how much the wing is pushed up

Let's take these 4 components into a simple drawing:

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-9bbca07ab4dc.png)

The black line represents the chord of the wing. This is the same with the outline of an wing:

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-f0c9683e824e.png)

We also have the resulting air-force, which is a line 90 degrees of the wing profile, based on the oncoming wind.

### Static and Dynamic pressure

For the example of Static and Dynamic pressure, I will stick to the example of a garden hose, pinched. This results in two things:

- Static pressure (A): This is the air pressure in the hose which will decrease when narrow and will increase again after the narrow part is over
- Dynamic pressure (B): This is the pressure of the water, the speed of the water, and this increases at the cost of static pressure

Take a look at this drawing, which makes more sense:

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-83e1e72cd4e8.png)

This basically works the same as the pitot-static system of an airplane, the static port measuring the static air pressure, as the pitot probe measures dynamic pressure. Inside of the measurement systems, there will be calculated the results which are Indicated Airspeed (IAS), Altitude and Vertical Speed (VS).

Dynamic pressure is measured with this formula:

- "P = q = 1/2 ρ V²"

This means:

- P: Total pressure
- Q: Dynamic pressure
- 1/2 ρV²: Also dynamic pressure but explained granular

Bernoulli's law states that for example water or air going into a narrow space at a certain speed, will also come out of that narrow space with that certain speed.

### Air flow around a wing-profile

The air will flow around a wing-profile. Because of the leading edge of the wing, the incoming air will divert up and down, bringing the flow-lines closer together.

Just like the two laws already predicted, the airflow will increase and the static pressure will decrease. At the leading edge of the wing, the lines will be closer together. Here the pressure is relatively low. Near the trailing edge of the wing, the flow lines will be less close. The speed of the airflow decreases and the pressure increases.

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-7ee45387fa20.png)

Under the wing, the airflow will have to make a smaller angle and path, causing the air to move at a slower speed but at an higher pressure.

### Upwash and Downwash

The upwash is an uplifting movement as result of the pressure differences. The leading edge of the wing needs to split the airflow. This point is called the "**stagnation point**", the point of air coming to a small temporary stop and then leaded over or under the wing. In the picture below, you can see that the airspeed is 0 at the stagnation point.

The downwash is a descending movement of the airflow after it hit the wings. As Bernoulli's law already stated, the dynamic pressure increases then the static pressure decreases, so the air above the wing goes at a faster speed.

Too see this all put into perspective, view this image:

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-f108f3b80f2f.png)
* Airspeeds are a reference

### An wing profile described

A wing profile has various parts, which we will describe now:

- Leading edge: The frontal part of the wing where the airflow first hit the wing
- Trailing edge: The aft-part of the wing where the airflow leaves the wing
- Chord: The imaginable line from leading edge to the trailing edge
- Camber line: The camber line which is the skeleton-line, is a line which is in the middle of the top and bottom
- Camber: The maximum distance between the camber line and the chord
- Thickness: The maximum distance between top and bottom. This will sometimes be referred as the "thickness-to-chord" ratio

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-d6d4e8ca01d7.png)

### Angle of incidence and Angle of attack

- **The angle of incidence** (AoI) (Instelhoek) is the angle between the longitudinal axis of the plane and the chord. This is how the aircraft is built and is by design, so the plane generates enough lift in straight and level flight.
- **The angle of attack** (AoA) (Invalshoek) is the angle between incoming airflow and the chord. This is the pitch angle you can set with the yoke, which controls the elevator.

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-a64ddda7e0fb.png) ![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-5a84de383c4d.png)

The angle of attack will often be reffered as "α". It also is an result of sum angle of incidence, the pitch angle and the glide angle.

### Glide angle

The glide angle (baanhoek in Dutch) is the angle between horizontal and the flight path. The flight path is the path the center of gravity flies through the air.

### The lift formula

The lift formula is an outline of the resulting airforce on a wing profile. Lift is dependent on these 3 things:

1. Dynamic pressure of the incoming airflow
2. The lift co-efficient
3. Wing surface

The formula goes like this:

- Lift = 1/2 ρ V² CL S

| 1/2 ρ V² | CL | Surface |
| :---: | :---: | :---: |
| The dynamic pressure of the incoming airflow (TAS) | Lift Coefficient | The surface of the wing |

So all these components work somewhat together to produce lift. This means the result of all must be positive, where one value can be less or more than another at certain parts of a flight. We will take a deeper look into the Lift components.

### Dynamic Pressure

The dynamic pressure is the pressure of the free airflow just before the wings. 1/2 ρ V² altogether is a sum of static and dynamic pressure, where V² means only the dynamic pressure. The V factor is equal to the True Airspeed. Headwind is also counted within this V factor, which means that the more headwind, the more lift.

Static pressure in this formula is also very important. This is directly dependent on the static air pressure in the air you fly in. The higher the static pressure, the more lift. This also means that if we climb with a plane to about 34.000ft where the air pressure is about 25% of the pressure on earths surface, you will need much more speed to retain a specific amount of lift.

### Lift coefficient

The lift coefficient is a sum of the angle of attack, amount of lift and drag. In a graph, this looks like this:

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-ce2d3128b18f.png)
* A fun fact is that because of the angle of incidence of a Cessna 172, a plane wil always have a higher angle of attack than 0.

This graph outlines that the more angle of attack we have, the more lift. However, there is a bount that this stops which is called the critical angle of attack. In a Cessna 172, this is around 15-16 degrees nose up. Pulling even more on the yoke causes the plane to stall and dip from the sky. This can be very dangerous at lower altitudes.

<a class="btn btn-primary" href="https://flightblog.justinverstijnen.nl/1-7-stalls/#stall-approach-recovery" target="_blank" rel="noreferrer">Stalls lesson</a>

A high angle of attack results in the air not gluing anymore to the wing but to transform into rotor flows. To get a better view of what exactly happens:

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-371e89355207.png)

### Wing Surface

The wing surface is a factor that directly influences the lift of a plane. In the formula, this will be in the value square meters (m²).

How bigger a wings' surface is, the more lift it can deliver. We can also do some things with our wings to produce even more lift as they increase the wing surface area. Think about:

1. Flaperons (flaps)
2. Slats (on airliners)

We set flaps on take-off to produce more lift at a lower speed. This means we need less runway to take-off from. When landing, we use more flaps to create more drag and decrease the speed. Flaps help us in these parts of the flight to have more time, see the runway a lot better and to descend in a much steeper line.

### Indicated Airspeed and Lift coefficient

Then in straight and level flight, there is a great connection between the speed and the lift coefficient. The lift equals the weight of the plane and the speed is higher than the amount of drag. However, if the angle of attack increases -> the lift coefficient will also increase. If preventing that the lift increases, the airspeed must be decreased.

- A *high* speed needs a *low* angle of attack
- A *low* speed needs a *high* angle of attack

### Symmetric and asymmetric wing profiles

- An Asymmetric wing profile is where the top of the wing has more camber, this is what most planes have
- A symmetric wing profile is where the top and bottom of the wing are the same, mostly in aerobatic planes

This also means something for the lift coefficient and the angle of attack performances. For example, a symmetric wing profile will start with 0 lift coefficient. This gives it somewhat less lift than an asymmetric profile, as shown in this graph:

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-0ae28aa5418f.png)

- Red: Asymmetric
- Green: Symmetric

Here an asymmetric wing profiles will eventually reach a lift coefficient at a negative angle of attack.

### Three-dimensional airflow over a wing

The airflow over the wings looks like this in three-dimensional setting:

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-3ed915c7c26d.png)

On the left, the airflow underneath and above the wing is illustrated and on the right we have the difference in pressure (Up = low and under = high). This difference in pressure will tend to flow to the wingtips. This movement actually causes the wake turbulence to happen. This movement however induces a decrease of lift and an increase of drag, **induced drag**, to be pronounced correctly.

### Wake turbulence

Wake turbulence (zogturbulentie) is caused by lift, and will show as two opposing turning rotors behind the wingtips. This is an excellent example of Newtons third law in action, which states that for every action in the universe there is an opposing reaction. The force of the lift creates an reaction in the form of wake turbulence.

The reaction of two opposing wings will cause this wake turbulence. The strength of the wake turbulence is affected by the amount of lift the plane generates. A Boeing 777 will generate lots of lift to fight its huge mass compared to a Cessna 172 and so generates more wake turbulence.

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-9a367d698770.png)

A good advice is if taking of behind an airliner, to wait for at least 3 minutes for the wake turbulence to completely dissipate. Heavy wake turbulence can cause huge problems as the airflow for light planes will be disrupted.

[I found a great video explaining the effects of wake turbulence and wingtip vortices here.](https://www.youtube.com/watch?v=xyKwrU7fRY4)

Some other facts:

- The strength of the wingtip vortices are caused by the amount of ligt
- The strength of the wingtip vortices are also caused by the angle of attach, where a higher angle of attack will generate more wingtip vortices
- The wingtip vortices are the strongest during take-off and landing
- An aircraft in clean configuration produces the most wingtip vortices
- Wake turbulence will move the direction of the wind

#### The risks of wake turbulence

The greatest risks of wake-turbulence are:

- Rapid roll-movements which will be so powerful steering against it will not be possible
- Structural damage to the plane
- Loss of height
- Greatly reduced climb performance
- Not enough lift at take-off (if taking of after a HEAVY aircraft)


### Wing shapes

The shape of an wing from the top view is called the wing shape. We have mostly two types of wing shapes:

- Straight wings
- Tapered wing

These wings also have some more properties:

- The **wing-root** is the part which is sticked to the fuselage
- The end part of the wing is called the **wingtip**
- The wing span is the total length of both wings from the wingtip of the left to the right wing

The distance of the wing leading edge to the trailing edge is called the chord as we already saw. Sometimes this chord is not a straight line. We then speak of a mean chord.

We can calculate the wing aspect-ratio using this formula:

*Aspect ratio = Wingspan divided by (/) the mean chord.*

Now the aspect ratio also helps producing lift. The higher this ratio, the more steep the lift-curve is. Take a look at this graph:

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-c67733ec5e49.png)

For reference, here a glider plane as a much steeper line than a fighter jet. This is like we already discussed, a result of the wingspan divided by the mean chord.

#### Wing surface

The wing surface is the total surface area of a wing. We calculate also the part above the fuselage, and is called the gross surface.

---

## Drag (3)

Drag (weerstand) is the resistance of the air a plane flies through. Oncoming wind slams into the cockpit, leading edge wings and wheels and this partly slows us down. More information about this component will be discussed further in this module.

We can feel drag especially when on a bike and going really fast (25-30 km/h or higher). You feel alot of upcoming air which slows you down. This is the exact same on a plane.

To let an aircraft actually fly, the thrust component of the engine must be higher than the total drag at all times. In an horizontal flight, the amount of drag is equal to the amount of thrust, bringing you forward in a constant speed.

### The drag formula

The drag formula is similar to the already discussed lift formula, and looks like this:

- Drag = 1/2 ρ V² CD S

| 1/2 ρ V² | CD | Surface |
| :---: | :---: | :---: |
| The dynamic pressure of the incoming airflow (TAS) | Drag Coefficient | The surface of the wing |

The only difference is that we replace the lift coefficient with the drag coefficient. This drag coefficient is also dependent on the angle of attack (AoA). More angle of attack means more drag, as the leading surface of the plane increases a bit.

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-2f45e64240c1.png)

### Types of drag

We have two types of drag, which we can separate into two categories:

- **Induced drag** (geinduceerde weerstand): Induced drag is caused by generating lift. When no lift is produced, no induced drag is produced either. We also can call this lift-dependent drag. This drag mostly happens at low speeds.
- **Parasite drag** (schadelijke weerstand): Parasite drag (schadelijke weerstand) is another type of drag, which increases as the speed increases. We also call this speed-dependent drag. This drag mostly happens at high speeds.

Here again we see the third law of Newton into place; where a specific force is reacted with another opposing force.

### Induced drag

So induced drag is produced and a reaction of generating lift. This is caused by the fact that the air over a wing has a lower pressure than under the wing. Because of this pressure difference and high pressure wants to flow to low pressure, some lift will leak away which causes some extra drag.

#### Induced angle of attack (AoA)

This air can also flow away to the wingtips, which causes some downwash behind the wings. This causes the incoming airflow to get a descending motion and causes the aerodynamic force to tilt somewhat. This also increases the drag component.

We can also have an induced angle of attack where the induced drag is counted from our effective drag.

#### Induced drag and speed

The induced drag is dependent on the lift as we already stated. The angle of attack also directly impacts this type of drag, where high angles of attack result in more induced drag. The induced drag also increases at low speeds and decreases at high speeds.

- High TAS: low induced drag
- Low TAS: High induced drag

#### Other factors for Induced drag

Some other factors that can influence the induced drag are:

- **Wing aspect ratio**: The aspect ratio (ratio between wingspan and mean chord) has a great effect on the induced drag. A thin and long wing (glider) has a short tip and therefore less room for air leakage from under the wing to above the wing.
- **Wingtip construction**: The construction of the wingtips are also influencing the amount of induced drag. An example is the Beech Bonanza V35 which has somewhat thicker wingtips where some fuel tanks are attached. This reduces the induced drag.
- **Ground effect**: In the ground effect the aerodynamic properties of a wing will have a minor difference. As there is less air mass just above the ground (0 - 2 meters), there is less room for wing vortices and downwash. This has some profitable results for us: more lift and less drag.

#### Ground effect

Ground effect gives us more lift, and therefore also a steeper lift coefficient curve. Keep in mind that leaving the ground effect changes the profit back to normal. Ground effect is at its most at a half wingspan above the ground. At 10% of a wingspan, the induced drag will decrease with almost 50%.

We have to take this change in properties into account, especially with landing:

- More lift means a slower descend or even some climbing
- Because of the decreased drag the plane will glide for a longer distance
- The decreased downwash will also decrease the angle of attach of the vertical stabilizer, making the nose descend a little

When taking off, keep this properties into account:

- When climbing out of ground effect, drag increases and lift decreases making us dip a little
- You can rotate with a slightly lower speed but you need ground effect to win speed to get to Vx
- In soft field take-offs you can use the ground effect to eject early from the ground and then win speed in the ground effect

### Parasite drag

Parasite drag (schadelijke weerstand) is another type of drag, which increases as the speed increases. This has nothing to do with producing lift.

Parasite drag can be divided into 3 categories:

- Form drag
- Friction-drag
- Interference drag

#### Form drag

Form drag is caused by the shape/design of the aircraft. As the air flows upon the leading edge, the air will be separated and a pressure difference occurs. By this separation the airflow gets disrupted, building up a new pressure opposing the movement direction. This is called wake.

A brief description is; the more streamlined an aircraft part is, the better the air will follow that part. This will cause less separation and less wake.

A great illustration of this in action:

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-29127908e35b.png)

This is the reason planes like the Cessna 172 have wheel-fairings.

#### Friction drag

When air flows over a fixed surface, air molecules will be braked due to this friction. These slower molecules then will also be slowed down by the molecules farther away from that surface. The further the molecules are away, the less this slowing force is.

Even though air feels light, it sticks slightly to the skin of the aircraft. This creates a thin layer of slowed-down air called the boundary layer. The smoother and cleaner the aircraft surface, the lower the friction drag. Rough surfaces, dirt, ice, rivets, or exposed parts can increase it.

In the cruising phase of a flight, the most drag you feel is an result of the friction drag.

#### Interference drag

Interference drag is caused by the close placement of all airplane parts close together. All those different parts have their own airflow which can (partly) disrupt each others airflow. This often happens where parts join together, such as the wing and fuselage, struts and wings, or landing gear and body. The airflow becomes more turbulent in these junction areas, which increases drag.

To minimize interference drag, aircraft manufacturers apply fairings to different parts, like from wing to struts.

### Total drag

The total drag of that we experience during flights is a sum of induced drag + parasite drag. We can see an example of this put into a graph:

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-06d2eaee385a.png)

Here we have in the middle a point where we have the least drag, this is where both amounts of drag are exactly the same. This is the V minimum drag (Vmd) speed. Often very similar to our best glide (Vg) speed, used to glide the most distance over a certain amount of distance.

### Speed stability of the total drag

We have a graph to get a better understanding of the two parts of drag and your airspeed.

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-cf51feabafdb.png)

- Red: Backside of the power curve, here is the plane not stable in terms of speed. A small decrease in speed means a increase in drag as the line is steeper. The speed will therefore decrease if not corrected with the throttle.
- Blue: Normal operating area, here the plane is more stable in terms of speed. Light corrections will be applied automatically due to the higher speed.

---

## Stall and spin flight (4)

A stall means exceeding the critical angle of attack. Stalling will occur when the plane has such a high pitch up momentum that the airflow is disrupted. The wing will instantly stop producing lift and the drag will increase substantionally.

Stalling does not neccesarily apply when flying at low speeds. When flying at a low speed, you need to pitch up to retain your altitude. There is a moment that the wings are so high up, causing a wing drop, nose drop or a heavy decrease of altitude occurs. This is a stall. But a plane can also stall when at its top speed, just because the airflow is disrupted.

In aerodynamic terms, we determine the cause of a stalling wing the behaviour of the boundary layer of the wing.

### Boundary layer

The boundary layer (grenslaag) is the small layer of air which hits the wing surface. At the surface of the wing, the flow of air will be slowed down as result of resistance. At the surface, the air will even be completely still (no-slip). From the surface the boundary layer will span up to where the flow of air is not disrupted anymore.

A good picture of this happening in both laminar and turbulent air, check out this picture:

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-34555f39fb28.png)

#### Laminar vs Turbulent

Laminar and Turbulent are each others complete opposites. Laminar beans that the air is very clean (organized) without movement, laminating the air over and under the wings. Turbulent means that this air is very unorganized which can happen by convection (rise of warm air), clean air turbulence or wake turbulence.

When the air is laminar, the following properties are:

- All air molecules will move from left to right
- Nice and orderly
- In parralel lines from each other

#### Boundary layer separation

When flying at greater angles of attack, the boundary layer will eject from the wing. This separation will result in a loss of lift, and is caused by the pressure gradient from the leading edge of the wing over the top.

From the leading edge of the wing, the pressure drops to a minimum. The point where this minimum is reached is at the front of this wing. After the front the pressure will increase again where at the trailing edge of the wing, the pressure is equal to just before the wing.

After the point of minimum pressure, the boundary layer has to flow in the opposite way, which is not easy by nature. This will increase to happen if the angle of attack also is increases until the wing is in a complete stall. At this stalling point, the separation point has made all its way to the leading edge of the wing.

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-476566d80d79.png)

{{% alert title="Info" color="info" %}}
A golf ball has some small dents in its skin. These have a very important cause, namely decreasing the size of the separation layer and so decreasing the total drag of the ball.
{{% /alert %}}

### Effects of increasing AoA

The effects of increasing the Angle of Attack (AoA) are the following:

- Stagnation point will change to the leading edge -> alerting the artificial stall warning of the Cessna 172
- The static pressure on the top side of the wing decreases
- At a asymmetric wing profile, the rpessure point will change forward to the leading edge at first but at hitting the critical angle back to the trailing edge
- The lift coefficient increases and decreases rapidly after hitting the critical AoA
- The drag coefficient increases slowly but very fast after hitting the critical AoA
- The total drag decreases at a certain angle but increases at a higher AoA

### Stall speed

When practicing stalls in a plane, we will close the throttle making the engine run stationary and keep our altitude. We do this because power-off stalls are less dangerous than power-on stalls. As we lose speed, we need to correct for it by increasing the angle of attack. All the way to the critical AoA. In the formula of lift coefficient, the lift-coefficient factor increases where the speed factor decreases. 

Just for fun, here is the formula again:

- Lift = 1/2 ρ V² CL S

| 1/2 ρ V² | CL | Surface |
| :---: | :---: | :---: |
| The dynamic pressure of the incoming airflow (TAS) | Lift Coefficient | The surface of the wing |

You can find the stall speed (Vs) in the pilot operating handbook (POH) of the plane. V speeds are always referenced at the Indicated Airspeed (IAS), which is what you see on your speed meter in the cockpit.

For more information about stalls and my stalls lessons, visit this page:

<a class="btn btn-primary" href="https://flightblog.justinverstijnen.nl/1-7-stalls/" target="_blank" rel="noreferrer">Stalls lessons</a>

### Stall speed factors

There are some factors that influence the stall speed of the plane. Because the speed is not a hard value, especially in the atmosphere which can change from time to time, they are all calculated using the following properties and are worst case scenarios:

- No flaps: Flaps help reducing the stall speed by around 5 knots on a Cessna 172
- Straight and level horizontal flight
- No engine power
- Center of gravity is in the front position
- The plane is at its maximum take-off weight (MTOW)

#### Weight

According to the lift formula, the lift factor must be equal to the weight factor to stay in the air. The lift factor must be higher if you want to climb. The POH always refers to the maximum take-off weight, so the worst case scenario here.

Womething which also is an option is to look at the ratio between weight and wing surface, which we call the wing loading:

- Weight/Surface = 1/2 ρ V² CL

How more the wing loading factor is, the more the stall speed.

#### Load factor

The load factor is the ratio between lift and weight. We will pronounce this in simple numbers: in straight and level flight, this ratio is 1. When manoeuvering, like turns or climbing this ratio will increase. At an angle of 60 degrees while climbing the load factor will be 2.

We can make this load factor visible with a little addition to the lift formula:

- Load factor x Weight = Lift = 1/2 ρ V² CL S

Here is described that the lift must not only be equal to the weight, but on the weight multiplied by the load factor. This makes clear that a change to the load factor has the same effect as on weight increase of difference.

For reference, here we have some numbers where we describe the load factor and increase of stall speeds in different turns:

|  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- |
| Load factor | 1 | 1,15 | 1,4 | 2 | 3,9 |
| Increase in stall speed | 0% | 7,5% | 19% | 41% | 97% |

{{% alert title="Info" color="info" %}}
Fun fact, the load factor is equal to the G-force.
{{% /alert %}}

#### Thrust

The thrust is the forward power the engine(s) and propellor(s) generates and will influence the stall speed in two ways:

- Thrust increases the vertical power/component
- Thrust increases the airspeed over the wings

At higher angles of attack, the thrust gets a upward component. The thrust reduces somewhat of the weight, where the lift decreases without stalling. The stall speed will get somewhat lower because of this when having full engine power.

Extra thrust on the propellor will also increase the flow of air over the inside - parts of the wings. The inside parts of the wings will get more air decreasing the stall factor there. This is great, as we keep control over the ailerons. However, when stalling, you must only steer with the rudder to avoid a spiral dive/spin.

#### Center of gravity

Another factor on the stall speed is the center of gravity. Ever tried to balance a straw on your finger? The point where the straw stays into plane without tilting to one of the sides is called the center of gravity.

In a plane we have also a center of gravity as we must be in balance. If the center of gravity is at the front section of the fuselage, the stall speed will increase. This is due to the extra correction the horizontal stabilizer needs to make to keep the plane level and this increases the stall speed. The POH refers to the most forward center of gravity possible while still inside of the Mass and Balance envelope as worst case scenario.

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-9379051b3709.png)

#### Turbulence

Turbulence is also a factor which can influence the stall speed. In turbulent weather, the wind speed and direction will constantly change. This results in a angle of attack which also changes in small differences. At low speeds with high angles of attack, a upward wind can pull the plane into the critical angle of attack, resulting in a stall.

### Stalls in climbing or descending turns

When climbing or descending, the wings have both a different angle of attack. This difference occurs because the outside wing has a longer distance than the inside wing. Because both wings are vertically making the same distance, the flight path of the outside wing has a flattened curve.

In a climbing turn, the angle of attack of the outside wing is the highest. If the speed decreases, the outside wing will stall first. At a descending turn, the inside will stall first. This is the reason the turn from base to final in the circuit is the most dangerous turn, which is commonly flown with somewhat more speed and a less steep turn (around 20 degrees in a Cessna 172).

While climbing:

- Outside wing stalls first

While descending:

- Inside wing stalls first

### Stall warning

When an aircraft is in a stall, the plane will lose altitude very fast and the plane can become uncontrollable. A stall warning is therefore very important, as this can (re)gain your attention. The stall warning sounds just before a real stall happens, giving you enough time to remediate the risk instead of fixing the stall.

We call it an approach to stall when a stall is around the corner but not fully developed. You can see this as the point in the lift coefficient curve where the line stops to increase.

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-ce2d3128b18f.png)

Sympthoms of an approach to stall are:

- Stall warning horn makes some noise
- Buffeting, this is an aerodynamic clue that the plane is about to stall where the drag of the separation layer takes over the lift making the aircraft shake somewhat
  - This effect is not that audible on a Cessna 172
  - It does on low-wing aircraft like Piper, Diamond Aircraft or Cirrus types
- Airspeed too low
- Controls becoming sloppy -> lower airspeed means lower air and less "grip"




{{< ads >}}

{{< article-footer >}}