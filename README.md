# Mini-Elevator-control-simulation-using-LabVIEW
we have 5 events:
              -wait for postion (waiting to click on the buttons)
             - click on button 0 (call the elevator on the ground floor)
              - click on button 1 (call the elevator to the 1st floor)
               -click on button 2 (call the elevator on the 2nd floor)
              - the click on button 3 (call the elevator to the 3rd floor)
-a message to explain the 1st step of this project 
-each transition from one floor to another is done by clicking on the sensors indicating the current
each transition from one floor to another is done by clicking on the sensor indicating the current floor and displaying its number in the "floor" indicator
-led A : "open" when you arrive at the destination 
we made the comparison with the sensor button in each event 
for example when we click on the button1 we can find in C-3,C-2,C-1,C-0
and clicking on C-3 sensor will disable C-0, C-1 sensor and wait for clicking on C-2 sensor
on the sensor C-2, this click will activate C-1 and deactivate C-3 etc...

# interface 
![image](https://user-images.githubusercontent.com/108087986/205009513-bb15b815-807b-4fd1-87b8-d2aa70880066.png)

