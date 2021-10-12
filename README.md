<h1 align="center">
  <br />
  PCB Business Card
</h1>

This is my custom PCB business card. At the end of 2020 I wanted a project to learn more about the principles of PCB design, so I decided to make a fully custom PCB that functions both as a microcontroller and as a business card. The final product looks like this: 

![business card](images/populated.jpg)
![card back](images/back.jpg)
![business card model](images/populated-model.png)

I used Altium to design the board. A lot of it was a learning experience so some aspects of the design probably don't follow best practices, but I'm very happy with how the design turned out. This is the schematic and x-ray view of the board: 

![schematic](images/schematic.png)
![schematic](images/xray.png)

After it was designed, I ordered all the necessary components and physically built the board using a reflow oven. The first attempt version was shorted due to a misaligned chip (in hindsight I definitely should have avoided hand placing a BGA MCU), but the the second attempt at soldering worked and the MCU can successfully be programmed. 

## Issues