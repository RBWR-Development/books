# Misc information

## Reactor types

Config board allows to pick a reactor type. Changing the reactor type only modifies the physics of the reactor, not the visuals of the control room.

1) Stable - This reactor has no natural circulation in the core, therefore at higher powers steam voids will kill the reactivity raise.  This reactor is very easy to control, just stop moving rods, and it will basically stay where it is. You will heavily rely on forced circulation flow to reach higher thermal powers.
 
2) Classic - This is the most realistic, classical BWR model. The reactor will have some natural circulation in the core, but still will be pretty stable on high powers due to steam voids production. As in real life, you should use both rods and forced circulation flow, but pulling rods only will give you full power too. (recommended for beginner users)

3) Self Circulating - This reactor is designed to have maximum of natural self circulation in the core. Therefore, negative void coefficient is non existent. This design is marginally stable and negative temperature coefficient of the core will stabilize it, but this effect is weak and other factors like xenon poisoning may make it temporarily unstable. Forced circulation flow is not required to operate this reactor model, but it can be used to make more precise power adjustments. PWR reactor would behave in similar way. (recommended for experienced users)

4) RBMK - While this reactor type in theory is a BWR its design is completely different. As it is based on graphite moderation, water is no longer acting like a moderator but more as neutron dampener. Therefore, with lower water density and creation of voids, the reactivity will raise. This reactor is unstable by design and can be difficult to control manually. Also, the forced circulation will have the reverse effect of slowing down the reactivity by removing steam voids.

## Suggested Operator positions

- Reactor and recirculation: 1 person
- Turbine main panel: 1 person
- Turbine local panel (U2): 1 person.  
        If no local panel operator is present the turbine operator is expected to walk down the turbine every 10 minutes max interval.  
- Electrical panel:   
        To be monitored by Turbine operator and shift supervisor.
- CST Deaerator and condenser: 1 person.
- Feedwater: 1 person.

## Operational limitations

- APRM:  
Norm: 100%  
SA+ : 120%
- Period:  
A- : 30s  
SA- : 20s  

- RPV Temperature:  
Norm: 287 °C  
A+ : 295 °C  
SA+ : 330 °C  

- Main steam pressure:  
Norm: 7100 kPa  
A+ : 8000 kPa  
SA+ : 9500 kPa  

- Turbine RPM:  
Norm: 3600 RPM  
A+ : 3700 RPM  
SA+ : 4000 RPM  

- Generator Load:  
SA- : -20 MWe  
A- : -1 MWe  
Norm: 1200 MWe  
A+ : 1500 MWe  
SA+ : 1600 MWe  
## Earning Points

To earn points: Check the network demand on a monitor on supervisor desk.  
You will have to generate +/-50 MW of power in relation to the demand (after subtracting site power use).  
If you do so, you will earn 1 point of every second.  
When using automatic control, you will earn only one point every two, three, four etc. seconds, depending on how many automatic systems are enabled. *In Unit #2 some other penalties may apply like wrongly setup deaerator or water levels outside of limits*. During offsite event and islanding points are earned same as in demand.

Every piece of equipment repaired will give you 100 points (if you don't mark something wrongly).  
Going down for maintenance when asked will give you 500 points, while successfully shutting down the reactor in case of offsite power loss will give you 650 points (minus what you have earned during islanding), while Chernobyl like test will give 500.

*Realistic startup in Unit #2 will give 300 points and 900 points if done without use of automatic control. Manual operations of Turbine in U2 will give additional 1 point per 3 seconds.*

