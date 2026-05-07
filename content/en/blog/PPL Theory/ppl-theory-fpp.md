---
title: "Flight Planning & Performance (FPP)"
slug: "ppl-theory-fpp"
date: 2026-05-03
tags:
- AI Generated Content
categories:
- PPL Theory
description: "This page contains my notes for the Flight Planning and Performance exam, where different aircraft performace calculations are described."
---

{{% alert title="Disclaimer" %}} For a live overview of my flight lessons, visit: <https://flighttools.justinverstijnen.nl/flightlessontracker>

This page can contain a collection of personal notes, steps to remember, finished and unfinished content. Please excuse brevity.

Do not use specific information given like fuel flow, landing/take-off distances for your flights. Always refer to the POH of your exact plane for flight preparation. My information is just for references that I used. {{% /alert %}}

## Introduction to Flight Planning and Performance (FPP) (1)

Before we step into an airplane we are required to know the aircraft performance in our particular situation. We can ask ourselves questions like:

- How much runway distance do we need for take-off and landing?
- How long does our climb phase take to our cruising altitude?
- What will our cruising speed?
- What will be our fuel usage?
- What will be our gliding distance?

Now these are not questions we will guess or something but we carefully calculate using numbers and graphs from the pilot operating handbook (POH) of our particular plane type.

In this module we will dive deeper in these questions and look at how we can make these calculations.

### Air density

The air density is a unit of how much air molecules a certain part of the air contains. We will pronounce this as kg/m³. In the International Standard Atmosphere which is the baseline reference for our pilots, the definition of this is at mean sea level that one cubical meter air (1000 liters) weighs 1,225 kilograms. So 1,225 kg/m³.

Air density is determined by a few factors like air pressure and temperature and derives from the general gas equation:

- **Air Pressure** (P): the air pressure in Pa (hPa x 100)
- **Gas constant** (R): this is a ratio between pressure, density and temperature. We mostly use the number 287 for this, the ratio for dry air.
- **Air temperature** (T): the air temperature at your airfield or cruising altitude in Kelvin, which is degrees celsius + 273.

Density (ρ)  =  P / (R x T)

An example calculation using todays numbers:

{{% alert title="Info" color="info" %}}
METAR EHLE 031055Z AUTO 24010KT 9999 FEW016/// BKN019/// BKN022/// 18/14 Q1010 TEMPO 6000 -SHRA SCT018CB BKN022
{{% /alert %}}

- Pressure: 1010 hPa x 100 = 101000 Pa
- Gas constant: 287
- Air temperature: 18 degrees celcius + 273 = 291

101000 : (287 x 291) = **1,209 kg/m³**

This tells us that today the air is less dense than ISA, meaning we can expect worse aircraft performance. A result of the less density is the higher temperature (18 degrees instead of 15 according to ISA).

### Density Altitude

To make this calculation somewhat easier for pilots to make, we have something called the Density Altitude. This is an altitude indication of how your aircraft will perform according to ISA. This makes these calculations much easier as we talk in altitudes instead of density like 1,225kg/m³. For example, if the density altitude is 3000ft we can expect performance as we are on 3000ft. This doesn't mean we are actually on that altitude but is the altitude corrected for the actual air density.

**Every 1c degree** deviation of ISA temperature, we take **120ft** as rule of thumb. If the air is colder than ISA this is a negative number, resulting in a lower altitude as the air is more dense. To calculate the density altitude we use the following formula:

_Pressure altitude + (ISA DEV x 120) =_

In the Netherlands, this density altitude often doesn't make huge differences, but in countries with high elevations this can make huge differences in flight performance. Especially if you don't take it into account. Let's make up an example of Sedona Airport in the USA, the training airport when playing Microsoft Flight Simulator.

{{% alert title="Info" color="info" %}}
METAR KSEZ 032035Z AUTO 03008KT 9999 CAVOK 37/16 Q1018 NOSIG(corrected for European readers)
{{% /alert %}}

As this airport has an elevation of 4825 ft, we are a huge portion away from sea level. The airport also is in the rocky mountains range making the temperatures huge.

To calculate density altitude, we need the pressure altitude first. This is the "ISA" altitude corrected for active air pressure. This is 4825 - 150ft = 4675 ft. As we have 5 hPa higher air pressure than ISA this is a little win. Now the density altitude.

37 degrees - 15 = 22 degrees of ISA deviation.

4675 + (22 x 120) = 7.315 ft Density altitude, which is almost 3.000ft higher

---

## Mass and Balance (2)

[https://flighttools.justinverstijnen.nl/unitcalculator](https://flighttools.justinverstijnen.nl/unitcalculator) [https://flighttools.justinverstijnen.nl/unitcalculator](https://flighttools.justinverstijnen.nl/unitcalculator) [https://flighttools.justinverstijnen.nl/unitcalculator](https://flighttools.justinverstijnen.nl/unitcalculator) [https://flighttools.justinverstijnen.nl/unitcalculator](https://flighttools.justinverstijnen.nl/unitcalculator)

The weight of an aircraft is a key factor to determine the flying performances. With the weight, we can calculate almost every V speed and the distance required for climb, take-off and landing. An aircraft is designed to operate in a specific weight range because exceeding this would result in unflyable planes with performance and controls not working as intended.

The key point here are:

- **Mass:** The weight force, at 1G this is equal to the weight but increases or decreases if G forces do
- **Balance:** The center of gravity point which must lie within limits

Why calculating Mass and Balance is being so important is partly described in this video, where the center of gravity of the plane shifted fatally to the aft part of the plane: [https://www.youtube.com/watch?v=hvZEr3IkLJI](https://www.youtube.com/watch?v=hvZEr3IkLJI)

As mass and weight are mostly the same (if not talking about G forces), I continue to use the word weight.

### Weight limits

We have two primary reasons why planes have maximum weights where they are certified for:

- **Structural limits:** An increase of weight means the planes' stressing factor is also increased, like the design-load.
- **Performance limits:** The performance of planes are heavily dependent on the weight, like take-off and landing distances but also the V speeds like stall speed, best climb speed, glide speed etc.

Aircraft manufacturers use these terms to indicate the limits of weight for their aircrafts:

| Limit name | Abbreviation | Description |
| --- | --- | --- |
| Maximum ramp weight |  | This is the overall maximum weight of the plane excluding calculated taxi-fuel. This is the limit of air plane before even moving to the runway. |
| Maximum take-off weight | MTOW | This is the maximum weight the aircraft can be at take-off. Above this weight the forces must work really hard, exceeding structural limits where the plane is not designed for. |
| Maximum zero-fuel weight | MZFW | This is the maximum weight of the aircraft excluding usable fuel. |
| Maximum landing weight | MLW | This is the maximum weight at landing. When landing, the full weight of the plane must get on the ground, possibly harder than needed. This often results in the maximum landing weight being lower than the take-off weight. |

Exceeding these weights will result in the plane being classified as un-airworthy.

[![jv-media-6000-c4ac0adadd19.png](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-fpp-6000/jv-media-6000-c4ac0adadd19.png)](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-fpp-6000/jv-media-6000-c4ac0adadd19.png)

When performing fuel and weight calculations and realising that we cannot take-off from a runway with a certain mass, you must re-do your calculations in terms of weight and fuel. To lower the amount of runway needed, you need to decrease the weight.

### Determining the weight

To determine an aircrafts weight, we have to calculate the actual weight of an aircraft. This is basically a sum of all known weights.

| Weight name | Abbreviation | Description |
| --- | --- | --- |
| Basic empty weight | BEW | The basic weight of a plane without usable fuel, including unusable fuel. It also includes structure, engine etc.This is a number weighed by the maintenance company (CAMO). My training Cessna 172 for example is more or less 700kg. |
| Crew and passengers weight | POB | The persons' weight of every pilot and passenger combined. Sometimes its better to "overguess" than actually asking people ;). |
| Baggage weight |  | The weight of the baggage. |
| Fuel weight |  | The weight of the usable fuel which we calculate based on the type of fuel. |

The sum of all those weights give us the actual of gross weight and will decrease during flight as the fuel is being consumed.

### Fuel weight

We calculate the weight of the fuel in our plane by picking default numbers based on the fuel we use. This is based on fuel density where we calculate the volume multiplied by density:

- Density of AVGAS/MOGAS/Car gasoline - 0,72kg/liter or 6lg/USG
- Density of Jet-A1: 0,84kg/liter or 7lb/USG

And we can use these numbers for conversion:

- 1 Pound (lb): 0,4536 kg
- 1 US gallon: 3,785 liter
- 1 Imperial gallon: 4,546 liter
- 1 quart (qt) = 0,95 liter (a quarter gallon)

> Tip: use my Unit conversion tool https://flighttools.justinverstijnen.nl/unitcalculator

### Fuel terms

To calculate fuel, we have different categories where we use different parts of fuel. We must have enough fuel on board for the complete flight, possible diversion and even more than that. As fuel calculations are very important we determine the amount using these terms:

| Fuel category | Used for |
| --- | --- |
| Taxi fuel | Taxiing to the runway excluding taxi after landing |
| Trip fuel | Take-off, climb, cruise, descend, approach and landing |
| Reserve fuel | Three types of reserve fuels needed in some situations |
| Contingency fuel | (+~5%) Fuel for unforeseen circumstances like wind, deferring routes, holding patterns |
| Alternate fuel | The fuel needed from destination to alternate including go around at destination, climb, cruise, descend, approach and landing on alternate. |
| Final reserve fuel | The minimum fuel that must be on board after landing. VFR flights this must be at least 30 - 45 minutes. This may also never be touched. |
| Extra fuel | All extra fuel on board for possible connected flights or flights to aerodromes without fuel station. |
| Block fuel | The total amount of fuel when departing from your parking place/ramp. |

We base the forseen fuel consumption on the numbers of the pilot operating handbook.

### Center of Gravity

The center of gravity (CG) is the central point of the gravity force. This point must be between the boundaries of the plane, as this has effect on the aircrafts performance. This center of gravity in general aviation aircraft is often determined in numbers of inches from a reference point. This reference point is called the "datum". The reference point are mostly:

- The firewall (wall between engine and cockpit)
- Forward point of the fuselage/propellor
- Wing leading edge

The pilot operating handbook will describe what the datum of your particular plane is. This point must be the same for that same aircraft at all flights.

[![jv-media-4511-55dae8418f5a.png](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/flight-lesson-2-4511/jv-media-4511-55dae8418f5a.png)](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/flight-lesson-2-4511/jv-media-4511-55dae8418f5a.png)

Here I created a mass and balance sheet for a Cessna 172 in my second flight lesson, fully within the technical limits of the aircraft.

- **Normal category flights** must stay within the red lines
- **Utility/aerobatic flights** must stay within the grey dotted lines

This states what the forward and after limits of the plane are in terms of center of gravity and how much weight we may carry. The whole flight, your weight and balance must be within the performance envelopes. This is the red area on the graph above.

To calculate the mass and balance, note all weights like done in the picture above and lookup the CG locations of your plane in the POH. Then its simply a multiply-sum where the weight must be multiplied by the CG location which gives the moment-number -> the resulting turning effect. Always use a method with a table and graphic to be sure about your aircrafts limits.

### Weight, Arm and Moment

To determine the center of gravity the moments are very important. We will talk about this three terms here:

- **Weight:** The force applied by an object due to its mass and gravity
- **Arm:** The distance from the reference point or pivot point to the line of action of the force
- **Moment:** The resulting turning effect produced by a force acting at a distance from a reference point or pivot point

[![jv-media-6000-901f341a550c.png](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-fpp-6000/jv-media-6000-901f341a550c.png)](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-fpp-6000/jv-media-6000-901f341a550c.png)

_Arm and moment in picture._

During the flight, the center of gravity always will shift somewhat because of thefuel consumption. This effect can be bigger when the tanks are further away from the center of gravity. When having wingtanks, this effect is small but be aware to stay within the envelope of the mass and balance scheme. This is also the reason we always calculate the zero fuel weight.

---

## Take-off and landing performances (3)

Calculating take-off and landing performances is crucial to us pilots as we want to know if we can land on a particular airport and runway with particular circumstances. To overcome shortage of runway, we calculate the distance we need according to the numbers in the POH. As the weather is never completely the same, we use the International Standard Atmosphere as reference point.

### Take-off distances

The take-off consists of 2 different phases:

- **Take-off run/Ground roll:** The first part where we power the engines to create enough speed and lift to get of the ground.
- **Initial climb:** The first climbing phase where we need to clear an altitude above the ground (AGL) of 50 ft or 15 meters.

[![jv-media-6000-8eba48553a30.png](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-fpp-6000/jv-media-6000-8eba48553a30.png)](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-fpp-6000/jv-media-6000-8eba48553a30.png)

In the middle of the whole take-off we have Vr speed which we start rotating to get in the air. This is the aircrafts' designed speed when taking-off is possible. We also know a Vlof speed which is the speed the plane comes loose of the ground, which is mostly close to Vr speed. We use this speed often in soft field take-offs to quickly get off the ground and win speed using ground effect.

### Available take-off runway lengths

Determining the take-off performance is part of flight preparation. The needed distances must fit within the available distances at that time. We use three different terms to indicate the available runway length:

- **Take-off run available (TORA):** The distance available for the the take-off run.
- **Take-off distance available (TODA):** The distance available for the take-off run and climb to 50ft.
- **Accelerate-stop distance available (ASDA):** The distance available for a rejected take-off.

In the most simple cases, these three values are exactly the same, but this is not always the case.

[![jv-media-6000-1ef7c651d9bf.png](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-fpp-6000/jv-media-6000-1ef7c651d9bf.png)](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-fpp-6000/jv-media-6000-1ef7c651d9bf.png)

#### Stopway and Clearway

Much airports around the world have additions to the runways for safety and ease of use. The 2 categories are:

- **Stopway** : A paved (verhard) addition to the runway only used for rejected take-offs (ASDA)

	- Sometimes on bigger airports this contains EMAS.
	- TORA + Stopway = ASDA
- **Clearway** : A clear-of-objects addition to the runway which can only be used for the climb to 50ft (TODA). This can also be sand or even water.

Sometimes, the stopway and clearway are combined as the image below states.

[![jv-media-6000-241272fcbd07.png](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-fpp-6000/jv-media-6000-241272fcbd07.png)](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-fpp-6000/jv-media-6000-241272fcbd07.png)

### Take-off distance factors

[https://flightblog.justinverstijnen.nl/ppl-theory-fpp/#density-altitude](https://flightblog.justinverstijnen.nl/ppl-theory-fpp/#density-altitude)

There are multiple factors influencing the take-off distance which are:

- Weight (Take-off weight)
- Wind
- Density altitude (density of the air, Dense = more lift)
- Runway state (Dry, Damp, Wet or Contaminated)
- Runway slope
- Flaperons (Flaps)

Let's dive into all these factors.

#### Weight (Take-off weight)

An increase of weight requires us to make more speed, therefore increasing the take-off distance. As the weight factor increases, we also need to produce more lift and also requiring in a higher speed (Vlof). You can find the impact of weight on the take-off distances in the POH.

A rule of thumb we can use in general aviation aircraft is: _an increase of 10% weight extends the required distance with 20%._

#### Wind

The wind also is a major factor in take-off distances. As an aircraft uses air masses to fly through, we get more of that air by flying into the wind, having Headwind. Therefore increasing our TAS and decreasing ground speed, resulting in needing less take-off distance.

- Headwind: Decreases take-off distance
- Tailwind: Increases take-off distance

To give an indication of the differences check out the picture below, altough with headwind we will be able to reach a much steeper climb:

[![jv-media-6656-umtjzra9givn.png](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/flight-lesson-7-6656/jv-media-6656-umtjzra9givn.png)](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/flight-lesson-7-6656/jv-media-6656-umtjzra9givn.png)

#### Density altitude

The density of the air is also an important factor of the take-off distance required. As we know, the density of the air is a factor in the lift formula:

- Lift = 1/2 **ρ** V² CL S

| 1/2 ρ V² | CL | Surface |
| :---: | :---: | :---: |
| The dynamic pressure of the incoming airflow (TAS) | Lift Coefficient | The surface of the wing |

The Rho (ρ) describes the density of the air. Altough the Rho and Airspeed are somewhat related as they both are in this formula:

- If density (ρ) decreases, Airspeed (V) must increase
- If density (ρ) increases, Airspeed (V) can decrease

Factors which influence the Density altitude and so our distances, which can abviously be a combined factor:

- High temperatures, warm air expands having less room for air molecules per m³
- Low air pressures due to high elevation or low pressure areas

In general aviation aircraft, the pressure altitude is enough as the tables and graphics in POH's already contain this correction for temperature.

{{% alert title="Info" color="info" %}}
To learn more about Density Altitude, check out: [https://flightblog.justinverstijnen.nl/ppl-theory-fpp/#density-altitude](https://flightblog.justinverstijnen.nl/ppl-theory-fpp/#density-altitude)
{{% /alert %}}

#### Runway state

The state of the runway is also an important factor for our required distances.













### Calculating take-off distances based on graphs

A skill we need to posess is calculating take-off distances using these graphs. An example can be found here:

[![jv-media-6000-c2d73c27c86a.png](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-fpp-6000/jv-media-6000-c2d73c27c86a.png)](https://sajvwebsiteblobstorage.blob.core.windows.net/flightblog/ppl-theory-fpp-6000/jv-media-6000-c2d73c27c86a.png)

The variables used are:

- Runway temperature: 25°C
- Airfield elevation: 2500 ft
	- Pressure altitude: 2041 ft
	- Density altitude: 3731 ft
- QNH: 1030 hPa
- Headwind: 5 KT
- Take-off weight: 2150 lb
- Flaps: 25 degrees

We start at the left, co-relating the temperature to the pressure altitude. This corrects the pressure altitude to the actual outside temperature (hey the Density altitude). Then we shift from there in a straight line to the weight coloumn. We pick the first line there and follow that to the actual weight. Then from that weight we set a straight line to the wind component. As we have 5 knots headwind, our take-off distance will be decreased so the line has to go down. We join the first downward line to take some margin into account, leaving us with a total take-off distance of 1640ft which is 500 meters.

You can also parralel the lines but this approach gives us some extra margin.

{{< ads >}}

{{< article-footer >}}