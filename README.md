# Altix-V1
This was a summer project to keep me occupied my freshman year of HS. Its not perfect but it works and is fun to mess around with. Strap it to a plane, rocket, drone, and get some flight metrics!


This was made with an STM32F405GTR6. You can find the F405 on lots of budget flight controllers for drones because they are a cheap and easy way to get into microcontrollers. 
The code for this was written in part by me, ChatGPT, and the KiCAD community. Huge shoutout to The KiCAD discord for putting up my electronics engineering questions. 

While the code works, it is not perfect and relies on some pretty complex math that takes some time for the FCU to complete, the calibration process takes aboiut 5 seconds and takes
lots of different altiutuide metrics and compares and converts them to AGL and ASL. G force measurement is also a fun feature and is great for trying to bend the wings off of you RC Plane and max out the
G-Max Metric. 
