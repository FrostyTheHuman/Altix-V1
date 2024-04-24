# Altix-V1
This was a summer project to keep me occupied my freshman year of HS. It's not perfect but it works and is fun to mess around with. Strap it to a plane, rocket, drone, and get some flight metrics!


This was made with an STM32F405GTR6. You can find the F405 on lots of budget flight controllers for drones because they are a cheap and easy way to get into microcontrollers. 
The code for this was written in part by me, ChatGPT, and the KiCAD community. Huge shoutout to The KiCAD discord for putting up my electronics engineering questions. As I upload this project, I also have the
revised version of this project complete but am in the process of writing code and making sure the data collection works well. Another note is that any I2C screen will work with this code as long as it isn't
something special. I used ssd1306 from amazon and it worked very well. This project was made with JLCPCB in mind and uses all of their electronics, i'm sure with a little fiddling you would be able to use PCBWay
or some other Manufacturer. 

While the code works, it is not perfect and relies on some pretty complex math that takes some time for the FCU to complete, the calibration process takes about 5 seconds and takes
lots of different altitude metrics and compares and converts them to AGL and ASL. The code is compiled from lots of other github Repos as well and I do not take credit for most of the SSD1306 code and the G-force Code. 
G force measurement is a fun feature and is great for trying to bend the wings off of your RC Plane and max out the G-Max Metric. 

If you have any questions or issues, feel free to reach out!

![image](https://github.com/FrostyTheHuman/Altix-V1/assets/68292775/298e3136-85d2-4ba0-9fb2-57e0611bdf9b)

Note: Some changes were made relating to resistor size for cheaper manufacturing, all changes are updated in the CSV file.
![image](https://github.com/FrostyTheHuman/Altix-V1/assets/68292775/6eccb981-ea29-4472-8606-c0225ee95039)

I added a couple pads for 3v3 or 5v Input from a flightcontroller, 1s Lipo Battery, or any other source.
The GPIO button was added for anything you need it to be, It could be used to store data, reset the Altix, or any use you see fit. 
Some I2C pads were also added for the ability add sensors or interface it with other electronics. 
![image](https://github.com/FrostyTheHuman/Altix-V1/assets/68292775/4f71d5e8-b070-45fb-a9c9-7eefd3199135)

![image](https://github.com/FrostyTheHuman/Altix-V1/assets/68292775/d7ac6de6-b2f3-4228-b732-d7f0b5be70a3)![image](https://github.com/FrostyTheHuman/Altix-V1/assets/68292775/f040fe8a-d697-4b1d-9b5e-df747eb86d72)


