VERTICAL WIND POWER PLANT
===================

Why not horizontal?
----

Horizontal turbines have higher efficiency. They surely are great in high heights where there is plenty of windspeed even in Germany.

Unfortunately in 10m height relative to ground in Germany the average windspeed is 3..4 m/s, in 900m ground-height over sealevel it's probably not more than 5.5 m/s.

Fun fact is that the huge windtowers in Germany even are built in a region with less windspeed  (approx. 4.5m/s in 10m height over ground). The crucial point is the huge height of the towers!! And the huge rotors that capture a lot of wind.


See here for more info:
http://www.dwd.de/windkarten




Component outline (might be messy):
---
Generator: Custom wound, low KV number.

Generator Output: 0.5..20KW. (Yes, if you build it large enough to catch enough wind, then this is possible IF and ONLY IF you have high wind speed. Unfortunately not in 99% of Germany. see http://www.dwd.de/windkarten)

To nevertheless reach that power level the wind turbine had to be hundreds of meters wide and high.


Voltage: 700V_DC. 400V_AC, 3phase. Prefer self-excitated generators! 
Prefer DC over AC for wind generators as otherwise dealing with frequency, harmonics, sinusoidal vs. pure sine (remember the generator is custombuild) will cause troubles. Another reason is utilisation of low wind speeds. It's easier to put DC to use (where voltage will be lower than V_nominal) than AC (where voltage and frequency will vary when the generator is not yet within the regulated speed margins).

Connection: DC side (battery bus) if DC generator is used. (Alternatively connect to the 3 phase AC line / cc voltage source converter AC side).

Turbine-Mount-Type: Vertical (not Savonius, which has 20% efficiency, yet lower efficiency than horizontally mounted wind turbines must be expected. It's impossible to extract all wind energy with a turbine. Theoretical maximum is said to be 58%.)


Reason: Horizontal has higher efficiency but vertical can withstand much (MUCH!) higher wind speeds. (ever wondered why all these giant horizontally mounted windspeeds stand still? either generator limit reached or structural failure danger. Yes, those have already been witnessed to disintegrate. Not that horizontally mounted is necessarily less good than vertical mount, both have their advantages. Vertically mounted is easier to build and starts to rotate in lower wind speeds, generating power earlier (Note that most sites never (NEVER!) will reach the windspeed most sold windmills have been tested with, approximately 10m/s, thus a 2KW windmill will never bring 2KW in power as wind speed not only varies but also is much much lower in average. Really there are very few places in world that show such high windspeeds regularly/often. 10m/s).),


Cut-in Wind velocity: ~1m/s
Cut-off Wind velocity: 28.8m/s (=103.7 km/h), due to safety reasons.

