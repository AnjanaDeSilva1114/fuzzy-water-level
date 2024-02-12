# Fuzzy-Water-Level-Controller

## Fuzzy Logic Level Control of a Cylindrical Water Tank
Consider a cylindrical water tank. Water enters the tank from the top at a rate proportional to the voltage, V, applied to the pump. The water leaves through an opening in the tank base at a rate that is proportional to the square root of the water height, H, in the tank. The presence of the square root in the water flow rate results in a nonlinear plant.

![alt text](https://github.com/AnjanaDeSilva1114/fuzzy-water-level/blob/main/q_image.png?raw=true)

where R is the radius of the tank, H is actual water height in the tank, V is the voltage applied to the pump, a (in m2 per minute) is a constant related to the flow rate out of the tank and b (in m3 per minute per volt) is a constant related to the flow rate into the tank. The goal is to design a fuzzy logic controller for the pump so that the water level is always at the desired level.

![alt text](https://github.com/AnjanaDeSilva1114/fuzzy-water-level/blob/main/qs.png?raw=true)

The approach to solving this assignment is followed by the steps below

● Create fuzzy variables

● Create three fuzzy logic membership functions

● Define fuzzy rules that applied on the membership functions

● Create an ODE function using the provided differential equation

● Apply initial values to compute the initial voltage by using the predefined fuzzy logic

● Compute the new height/height change using the current-voltage

● Run a for-loop for several iterations of the last two steps

## Results
### Membership function
![alt text](https://github.com/AnjanaDeSilva1114/fuzzy-water-level/blob/main/MembershipFunction.JPG?raw=true)
### Water height and applied voltage
![alt text](https://github.com/AnjanaDeSilva1114/fuzzy-water-level/blob/main/Results_P1.JPG?raw=true)
### Water height and applied voltage with time variable a
![alt text](https://github.com/AnjanaDeSilva1114/fuzzy-water-level/blob/main/Results_P2.JPG?raw=true)
