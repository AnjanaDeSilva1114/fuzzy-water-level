# Fuzzy-Water-Level-Controller

## Fuzzy Logic Level Control of a Cylindrical Water Tank
Consider a cylindrical water tank. Water enters the tank from the top at a rate proportional to the voltage, V, applied to the pump. The water leaves through an opening in the tank base at a rate that is proportional to the square root of the water height, H, in the tank. The presence of the square root in the water flow rate results in a nonlinear plant.

![alt text](https://github.com/AnjanaDeSilva1114/fuzzy-water-level/blob/main/q_image.png?raw=true)

where R is the radius of the tank, H is actual water height in the tank, V is the voltage applied to the pump, a (in m2 per minute) is a constant related to the flow rate out of the tank and b (in m3 per minute per volt) is a constant related to the flow rate into the tank. The goal is to design a fuzzy logic controller for the pump so that the water level is always at the desired level.

![alt text](https://github.com/AnjanaDeSilva1114/fuzzy-water-level/blob/main/qs.png?raw=true)

The method for completing this assignment involves the following steps:

● Establish fuzzy variables.

● Develop three fuzzy logic membership functions.

● Specify fuzzy rules to be applied to the membership functions.

● Formulate an Ordinary Differential Equation (ODE) function based on the given differential equation.

● Utilize initial values to determine the initial voltage through the predefined fuzzy logic.

● Calculate the new height or height change using the current voltage.

● Implement a for-loop to iterate through the last two steps multiple times.

## Results
### Membership function
![alt text](https://github.com/AnjanaDeSilva1114/fuzzy-water-level/blob/main/MembershipFunction.JPG?raw=true)
### Water height and applied voltage
![alt text](https://github.com/AnjanaDeSilva1114/fuzzy-water-level/blob/main/Results_P1.JPG?raw=true)
### Water height and applied voltage with time variable a
![alt text](https://github.com/AnjanaDeSilva1114/fuzzy-water-level/blob/main/Results_P2.JPG?raw=true)
