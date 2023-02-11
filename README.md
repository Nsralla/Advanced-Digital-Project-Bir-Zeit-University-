# Advanced-Digital-Project-Bir-Zeit-University-
The task is to design a solution to real problem which is the traffic light design for two roads. 
You will design a traffic light controller for the highway and farm road intersection shown in Figure 1. The traffic light controller outputs four 2-bit signals, highway Signal 1 and highway signal 2 and farm Signal 1 and 2, for the highway road and the farm road, respectively. The following encoding is used for both signals: 
00 : Green 
01 : Yellow (when changing from green)
10 : Red
11 : Red-Yellow (when changing from red)
Description of the signals:
Your design has 3 inputs which are:
“Rst” : It returns the design to state 0, and counter to 0. 
“Go”: The default is that go = 1 in order to change between different states. However, if go is forced to 0 then the counter will stop counting (freeze).
“clk” : Synchronous system.
After building the design, you have to build a simple testbench which will implement a test for all cases (states). 
<img width="962" alt="image" src="https://user-images.githubusercontent.com/122102030/218268597-ae2eab30-1bad-450b-a14a-817488b68bf5.png">


