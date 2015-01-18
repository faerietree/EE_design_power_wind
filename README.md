VERTICAL WIND POWER PLANT
===================

Why vertical axis flow turbine (VAFT)? why not horizontal? (HAFT)
----

Horizontal turbines have higher efficiency and high rentability for large systems.
In high heights where there is plenty of windspeed even in common low wind speed countries (like Germany).

Unfortunately in 10m height relative to ground in Germany the average windspeed is 3..4 m/s, in 900m ground-height over sealevel it's probably not more than 5.5 m/s.

Fun fact is that the huge windtowers in Germany even are built in a region with less windspeed  (approx. 4.5m/s in 10m height over ground). The crucial point is the huge height of the towers! And the huge rotors that capture a lot of wind (as well as the shape of the rotors that allow for a constant Reynold-number along almost the entire blade length - contrary to simple netherland-windmill drag rotors).


Despite the advantages of the horizontal turbine for large scale systems and high flowspeeds (where structural failure is imminent if the area in standstill is too big), the vertical axis turbine is easier to build (legally). It also allows for direct generator coupling to a axial flux motor if the RPM and torque match, which often requires a custom-built (and designed!) generator.


Example information on windspeed:
---
http://www.dwd.de/windkarten


Goals/Requirements:
---
All parameters are nominal/target values of *this* design. They neither resemble minima nor maxima. It depends on the design and required energy sources.


*It's impossible to extract all wind energy with a turbine. Theoretical maximum is said to be 58% (Betz-Limit).)*

###Flow:
speed: 4..7m/s
=> Large effective flow area required. => Increased efficiency [Thesis F. Furtmayr].

Turbine-Mount-Type: Vertical


Reason: Horizontal has higher efficiency but vertical can operate (!) in higher wind speeds. (ever wondered why all these giant horizontally mounted windspeeds stand still? either generator limit reached or structural failure danger, thus minimizing Tip speed ratio to 0 to reduce effective area in the flow).

Not that horizontally mounted is necessarily less good than vertical mount, both have their advantages. Vertically mounted is easier to build and starts to rotate in lower wind speeds, generating power earlier (Note that most sites never (NEVER!) will reach the windspeed most sold windmills have been tested with, approximately 10m/s, thus a 2KW windmill will never bring 2KW in power as wind speed not only varies but also is much much lower in average. Really there are very few places in world that show such high windspeeds regularly/often. 10m/s).),


Cut-in Wind velocity: ~1m/s
Cut-off Wind velocity: 28.8m/s (=103.7 km/h), due to safety reasons.
###Generator:
Either custom wound, low KV number
OR
transmission driven induction motor as generator (due to high availability on scrap yards).

Power: .1..3KW
*If you build it large enough to catch enough wind, then even more power is possible IF and ONLY IF you have high wind speed. Unfortunately not in 90+% of Germany. see http://www.dwd.de/windkarten
To nevertheless reach that power level the wind turbine had to be hundreds of meters wide and high.*

Voltage: 570V_DC. 400V_AC, 3phase. Prefer self-excitated generators if off-grid (island) operation only and if batteries or rectifiers or inverters are used anyway!
=> Design voltage for electronics: 700V__DC 

If off-grid, then prefer DC over AC for wind generators as otherwise dealing with frequency, harmonics, sinusoidal vs. pure sine (remember the generator is custombuild) will cause troubles. Another reason is utilisation of low wind speeds. It's easier to put DC to use (where voltage will be lower than V_nominal) than AC (where voltage and frequency will vary when the generator is not yet within the regulated speed margins).

Connection: DC side (battery bus) if DC generator is used. (Alternatively connect to the 3 phase AC line / cc voltage source converter AC side).

Turn on turbine RPM: 33% of nominal RPM (?)

