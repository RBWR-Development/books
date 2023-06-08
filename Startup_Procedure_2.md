The reactor can be operated in 3 modes: SRM, IPR and Run. Run mode can be enabled above 5% reactor power and can be used without any restrictions between 4%-100% of reactor power (it will SCRAM below 4%). SRM/IPR modes are used for startup only and have several restrictions:

- only one rod can be pulled at a time and according to a predefined pattern
- next rod is available when previous rod is pulled to 20%
- when all rods are at 20%, now rods can be pulled to 40% and so on
- Autocontrol and autobalancer is not available

SRM mode is used for low power startup. SRM should be lowered into the core by few percent and SRM indicator should be monitored. As equivalent rods position increases, SRM should be lowered to reach a depth similar to equivalent rods position. This way SRM can be monitored in the region just above the rods. Once SRM reaches half of the scale reactor mode should be changed to IPR. 

- IPR will scram the reactor if out of range (below 10% or above 90%)
- IPR level has to be incremented when power reaches the blue region to prevent scram
- Above 5% power reactor should be switched to Run mode, so it won't scram due to IPR range

This procedure is introduced in BWR reactor because it tends to be not very stable at low powers, where no negative coefficient play a role yet, and also to balance out reactivity in the whole core. The pattern is coded into a system and flashing rod should be selected, then pulled to around 20%. Above that value, the rod block will prevent any further pull. In the meantime another rod would start flashing showing the sequence. This procedure should be repeated until 5% of power is reached.

IPR has 8 levels, and they have to be incremented when indication nears 90% red line. Although it cannot be switched to high level immediately as it will also scram the reactor when the indication is below red 10% line. On 8th level, reactor has to be switched to run mode to prevent scram from IPR. Also remember to change IPR to level one after a scram, so restart is possible.