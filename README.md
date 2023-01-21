# Spektrum Smart G2 Battery No Communication

I recently had a Spektrum 5000mAh 3s 50C G2 smart battery stop charging. We were thinking it was yet another battery that completely discharged itself because the smart stuff cant turn off. but it was still reading 11.17V on the main lead. Which isn't charged but definitely not low enough for the charger to not recognize it. Not great but not a huge deal if it was a G1 as then you could just charge it like a normal "dumb" LiPo. But because its G2, if the battery isn't recognized on the charger then you cant balance charge it. So I hooked it up to an oscilloscope to see if it was bad data or if it straight up not communicating.

## Table of Contents

- [Observations](#observations)
	- [Good Battery](#good-battery)
	- [Bad Battery](#bad-battery)

## Observations

### Good Battery

For the good battery I have to use a G1 5000mAh 3s 30C since I couldn't find another G2 of the same type. 
First thing I check of course is the voltage and its at 12.5V.

![alt text](https://github.com/davidflypei/Spektrum-Smart-G2-Battery-No-Communication/blob/main/Images/good-main-volt.jpg?raw=true)

I did also check the voltage on the signal pin 