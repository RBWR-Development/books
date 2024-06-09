# Reactor Control panel

## Reactor Control

Reactor is controlled primarly by the means of movement of control rods. Rods are pulled out of the core and pushed back inside with Rods Control lever (*in Unit #2 Rods Movement switch*) in either Group Control or All Control. In Group Control only selected rods will move, while in All Control all rods will be moved equally. Movement speed can be chosen between S - Slow, M - Medium, F - Fast. In Group Control rods can be moved much quicker and the speed depends also on how many of them are selected.

## Reactor Period

Several indicators are used to control reactor power. The most important indicator is the Reactor Period. Reactor Period tells us in how many seconds power of the reactor will triple (exactly in how many seconds it changes by the factor of e = 2.71...). Low reactor periods ~ 30 seconds indicate quick changes, large reactor periods ~ 1000 indicate slow changes. When period is at infinity the reactor is at stable constant power. Negative periods indicate power dropping.

At all time positive periods should be held above 30 seconds and reactor will SCRAM if period is below 20 seconds. For high power operations (above 10% of power) much larger periods are recommended 100-500 seconds.

## Source Range

Source Range Monitor (SRM) is used at very low powers during initial reactor startup. This indicator doesn't provide direct reactor power it just counts the neutrons. It should be used up too few thousands of counts when operator should switch to IPR.

## Intermediate Power Range

IPRM (Intermediate Power Range Monitor) consists of a 0-100% gauge and a 6 level selector (*8 levels in Unit #2*). Selector initially should be at level 1 while IPRM is observed. With growing power IPRM will raise and when around 75% (3/4 of the scale) IPRM level should be incremented to level 2. At this moment IPRM will drop to around 30% and will start to raise again. This procedure should be repeated until maximum level is reached. While IPRM doesn't give a direct measurement of reactor power it can be estimated by at which IPR level we are at the moment. Low levels indicate low power, while level 6 (*level 8 for Unit #2*) indicates heat gaining powers (around 1% of total reactor power)

## Average Power Range

APRM (Average Power Range Monitor) gives the most reliable power of the reactor in percent of maximum operating power. It is used in whole range between 1%-100%. APRM is an average of several LPRMs (Local Power Range Monitors) which measure power output at different locations in the core. Power should never exceed 100% of APRM and reactor will SCRAM at 125% of APRM.

## Core monitor

Core monitor shows % of rods pulled and % of maximum power for each group of rods individually. Vertical slices of the core can also be selected to see powers for each cell in the core on different depths (*In Unit #2 fuel temperatures instead of powers are shown*). Rods should be pulled individually in such a manner that total power between all groups are more or less balanced. Automatic Balancer can also be used for that. Usually the inside rods heat up quicker than outside rods although it's not always the case as this may depend on fuel quantity in each rods and xenon amount. Recirculation imbalance can also affect imbalance in parts of the core.

## Unit 2 realistic mode

*The reactor can be operated in three modes: SRM, IPR, and Run. The Run mode can be enabled above 5% reactor power and can be used without any restrictions between 4% to 100% of reactor power (it will SCRAM below 4%). SRM/IPR modes are used for startup only and have several restrictions.*

- *Only one rod can be pulled at a time, following a predefined pattern.*
- *The next rod becomes available when the previous rod is pulled to 20%.*
- *When all rods are at 20%, the rods can be pulled to 40%, and so on.*
- *Autocontrol and autobalancer are not available.*

*SRM mode is used for low-power startup. SRM should be lowered into the core by a few percent, and the SRM indicator should be monitored. As the equivalent rod's position increases, SRM should be lowered to reach a depth similar to the equivalent rod's position. This way, SRM can be monitored in the region just above the rods. Once SRM reaches half of the scale, the reactor mode should be changed to IPR.*

- *IPR will scram the reactor if it goes out of range (below 10% or above 90%).*
- *The IPR level has to be incremented when the power reaches the blue region to prevent a scram.*
- *Once the power is above 5%, the reactor should be switched to Run mode to avoid a scram due to IPR being out of range.*

*This procedure is introduced in BWR reactors because they tend to be unstable at low powers, where no negative coefficient plays a role yet. It is also used to balance out reactivity in the entire core. The pattern is coded into a system, and the flashing rod should be selected, then pulled to around 20%. Beyond that value, the rod block will prevent any further pulling. Meanwhile, another rod will begin flashing, indicating the sequence. This procedure should be repeated until 5% power is reached.*

*IPR has 8 levels, and they must be incremented when the indication nears the 90% red line. However, it cannot be switched to a high level immediately, as it would also scram the reactor when the indication is below the red 10% line. When reaching the 8th level, the reactor must be switched to Run mode to prevent a scram from IPR. Additionally, remember to change IPR to level one after a scram to enable a restart.*

*Realistic startup will give 300 points and 900 points if done fully in manual (including Turbine Control Room)*.
