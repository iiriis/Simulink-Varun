# Simulink-Varun

A simulink model of a water pump controller

## Inspiration
After watching and experiencing turning off and on our household water pump manually, it was really hectic and frustrating. It happened many times when you stay alone at home and while using the bathroom, the overhead tank got emptied and you were hassled. Even the opposite happened when you turned on the pump and forgot to switch it off, causing heavy water and power wastage. This leads us to make a circuit that can automatically turn the pump off or on depending on the level of water.

## What it does
In this project, we designed to build a water pump controller that will automatically turn ON or OFF the water pump when required. We have modeled that in Simulink. The circuit uses no microcontrollers ensuring much stability and cost-efficient. The approach is made using simple digital circuitry. When the water inside a tank falls below a certain threshold the circuit will turn the pump OFF automatically and upon the tank getting emptied, it will turn on the pump again. 

## How we built it
We have made a model in Simulink. Inside it, we used few discrete logic components like three NOR gates, and one AND gate. Firstly we modeled the tautology in a truth table, i.e when the output needs to go high and low depending upon the input conditions. After finding the truth table we went for a boolean simplification with the K-Map. After finding the simplified boolean expression we used NOR gates and a AND gate to achieve the circuit. After making the connections we used a scope and stepped the simulation for the results. 

## Challenges we ran into
The Simulink was going unstable sometimes, creating errors in the outputs and that was a bit frustrating. 

## Accomplishments that we're proud of
Able to create the simulation properly, overcome the instability of the outputs was a great achievement. Also, we are going to have our exams from the day after tomorrow, but yeah with great teamwork, we loved building the hack. :)
 
## What we learned
We learned a lot about Simulink. Modeling in Simulink, and being able to use the timestep functions, also being able to use the step hold function.

## What's next for Simulink Varun
Making a better model, containing a wireless system, that too modeled in Simulink. 
