# SIMULATION OF REGULATED POWER SUPPLY

## AIM:
To design and simulate the a complete AC to DC power supply using LTspice consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode voltage regulator and load, and to observe the output waveform at each stage.

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1.Double click on LT-Spice icon.

2.New schematic window open.

3.Pick and paste the required component from the library and draw the transformer circuit using AC source, L1, L2 and coupling.

4.Run the simulation and observe the transformer secondary output.

5.Pick and place four diodes and draw the bridge rectifier circuit.
 
6.Run the simulation to obtain the rectified waveform.
 
7.Place the smoothing capacitor across the rectifier output.

8.Run the simulation again to view the filtered DC waveform

9.CAdd the Zener diode regulator with a series resistor and connect the load resistor.

10.Right-click each component and set the required values.

11.Save the file with a suitable name.

12.Click Run → Advanced→ Transient Analysis and set the stop time (e.g.,60 ms).

13.Click Run, and place the probe at each stage to observe: Transformer output, Rectifier output, Filtered output, Regulated output, Load voltage.



## CIRCUIT DIAGRAM:

<img width="903" height="412" alt="image" src="https://github.com/user-attachments/assets/4ff0234a-b7b2-46d6-aaab-b9c8e427c520" />


## AC INPUT WAVEFORM:

<img width="779" height="390" alt="image" src="https://github.com/user-attachments/assets/d67c9419-c073-49d2-a695-7e2066a0ec6b" />


## OUTPUT GRAPH:
## SIGNAL OUTPUT(WITHOUT FILTER)

<img width="778" height="393" alt="image" src="https://github.com/user-attachments/assets/57098c94-e199-4c45-9d0b-8473980e6853" />

## SIGNAL OUTPUT(WITH FILTER)

<img width="776" height="388" alt="image" src="https://github.com/user-attachments/assets/5d9f9182-5b9f-459f-bf13-5d78bc83eb1f" />



## RESULT:
Thus the output waveform at each stage was observed and analyzed. A stable regulated DC output was obtained at the load of RPS using LT-spice is simulated and verified. 
