# AUTOMATIC CONTROL

## Purpose
Reactor automatic thermal power control is used to automate the process of reaching desired power and holding the setpoint.

## In unit-1
In unit-1 the automatic thermal power regulator can be found between the manual control rod operation panel and the recirculation control panel.

## This panel consists of 3 main elements
 - Pre designated power setpoints.
 - Manual setpoint adjustment switch.
 - Regulator mode selector.

### Pre designated setpoints
The pre-designated setpoints are the most commonly required power setpoints required by the operators. These setpoints are:

- 1% APR  
    Used when initially starting the plant 1% APR is the point reffered to as POAH(the point of adding heat), this is the point where there is enough self sustained nuclear fission in the core to generate a noticable ammount of heat leading to a controlled system warmup.

- 5% APR  
    At 5% APR sufficient thermal power is generated to commence the turbine startup.

- 10% APR  
    At 10% APR sufficient thermal power is generated to synchronize the turbine to the grid and start providing power, **HOWEVER:** *This should not be done before a main steam pressure of 7100 kPa is reached*.

- 20% APR  
    At 20% APR we build pressure to **7100 kPa** and then the auto pressure hold mode is enabled.

- 30% APR  
    30% APR is the upper rod block safety limit.


### Operational modes
on the Unit-1 Automatic thermal power regulator there are 2 modes of operation:

- Absorber movement mode (LEFT BUTTON)  
    In this mode the automatic controller utilizes its authority over rodmovement. Inserting control rods to lengthen period and pulling control rods to shorten period.

- Recirculation mode  
    In recirculation mode the auto control utilizes its authority over pump speed of the 2 reactor recirculation pumps to increase or decrease the recirculation flow thus changing reactor power.


## In Unit-2

### Operational modes
In Unit-2 the auto control has 3 modes:  

- Circulation mode  
    in Circ mode the auto control utilizes its authority over pump speed of the 2 reactor recirculation pumps to increase or decrease the recirculation flow thus changing reactor power.   

- Rods mode  
    In rods mode the auto control utilizes its authority over rodmovement to lengthen or shorten period by inserting or pulling rods respectively.  

- Group mode  
    In Group mode the system acts like rod mode but only the selected groups can be moved.


## Behaviour

The computer will try to smoothly reach the desired level and then hold it. 
 
Oscillations might occur due to processes affecting reactor power like negative temperature coeficient or xenon levels.

Changes in circulation flow is not effective at low temperatures and reactor powers.
it can quickly reach its limit. This will be signaled with a sound notification. In that case you have change mode to absorber movement mode.  
You can also control the other system manually.   
For example, if you see that due to xenon burnoff the computer is reducing circulation flow close to 0% it would be wise to insert control rods manually to give circulation system more margin.

## Operation
the automatic thermal power control system operation occurs in 2 phases.  
The Absorber regime and the circulation regime.  

- Absorber regime.  
    In absorber regime the thermal power should be controlled with only the moveable absorbers and both recirculation pumps at minumum power (28%).  
    During this regime the trip setpoint is set to 40% APR. Once this point is reached the changeover to recirculation regime should take place.  

- Recirculation regime.  
    If done correctly the reactor should be at an APR of +- 40%. At this point it is recommended to further raise power using the recirculation pumps.  
    However during system tests the recirculation control setting on the automatic regulator has proven to be unstable. This is why it is reccomended to use the power to flow operating map.  
    To do this you set the APR setpoint to the desired level and then rev up the circulation pumps to the percentage determined by the power to flow operations map found on the back wall of the control room.  
    Ramping down can be done in the same manner.  
    **WARNING:** Take caution when ramping up power as a too high power rate can destabilize the plant!