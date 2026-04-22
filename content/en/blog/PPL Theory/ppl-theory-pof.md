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

### Angle of incidence vs. Angle of attack

- **The angle of incidence** (Instelhoek) is the angle between the longitudinal axis of the plane and the chord. This is how the aircraft is built and is by design, so the plane generates enough lift in straight and level flight.
- **The angle of attack** (Invalshoek) is the angle between the longitudinal axis of the plane and completely horizontal. This is the pitch angle you can set with the yoke, which controls the elevator.

![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-a64ddda7e0fb.png) ![](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-pof-5667/jv-media-5667-5a84de383c4d.png)


### Glide angle

The glide angle (baanhoek in Dutch) is the angle between horizontal and the flight path. The flight path is the path the center of gravity flies through the air.



{{< ads >}}

{{< article-footer >}}