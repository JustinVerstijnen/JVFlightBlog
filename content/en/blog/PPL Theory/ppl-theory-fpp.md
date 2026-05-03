---
title: "Flight Planning & Performance (FPP)"
slug: "ppl-theory-fpp"
date: 2026-05-03
tags: 
categories: PPL Theory
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

****

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
