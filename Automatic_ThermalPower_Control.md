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
    - Used when initially starting the plant 1% APR is the point reffered to as POAH(the point of adding heat), this is the point where there is enough self sustained nuclear fission in the core to generate a noticable ammount of heat leading to a controlled system warmup.

- 5% APR
    - At 5% APR sufficient thermal power is generated to commence the turbine startup.

- 10% APR
    - At 10% APR sufficient thermal power is generated to synchronize the turbine to the grid and start providing power.

- 20% APR
    - At 20% APR we build pressure to **7100 kPa** and then the auto pressure hold mode is enabled.

- 30% APR
    - 30% APR is the upper rod block safety limit.


### Operational modes
on the Unit-1 Automatic thermal power regulator there are 2 modes of operation:

- Absorber movement mode (LEFT BUTTON)
    - In this mode the automatic controller utilizes its authority over rodmovement. Inserting control rods to lengthen period and pulling control rods to shorten period.

- Recirculation mode
    - In recirculation mode the auto control utilizes its authority over pump speed of the 2 reactor recirculation pumps to increase or decrease the recirculation flow thus changing reactor power.


## In Unit-2

### Operational modes
In Unit-2 the auto control has 3 modes:  
- Circulation mode
    - in Circ mode the auto control utilizes its authority over pump speed of the 2 reactor recirculation pumps to increase or decrease the recirculation flow thus changing reactor power.     
- Rods mode
    - In rods mode the auto control utilizes its authority over rodmovement to lengthen or shorten period by inserting or pulling rods respectively.
- Group mode
    - In Group mode the system acts like rod mode but only the selected groups can be moved.


## Behaviour

The computer will try to smoothly reach the desired level and then hold it. 
 
Oscilations might occur due to processes affecting reactor power like negative temperature cöefficient or xenon levels.

Changes in circulation flow is not effective at low temperatures and reactor powers.
it can quickly reach its limit. This will be signaled with a sound notification. In that case you have change mode to absorber movement mode.  
You can also control the other system manually.   
For example, if you see that due to xenon burnoff the computer is reducing circulation flow close to 0% it would be wise to insert control rods manually to give circulation system more margin.