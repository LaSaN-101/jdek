![Screenshot 2025-02-01 225132](https://github.com/user-attachments/assets/dc653433-6df0-49e9-9b65-61813ffa617c)# Welcome to JDEK
## An open source macropad with <br> 30 buttons and programmable 3.5 inch touch lcd display

<img src="/Images/1.jpg" width="480" height="320">

## There are two main folders for Code and CAD files.

### CAD PART
CAD files were created in Fusion and are intended to be laser cut.

I hade 3mm clear acrylic sheet in mind when designing.

If you want thicker you will need to thicken the slots in the stand base 
or just cut thicker face and base plates and 3mm mid plates. 


<img src="cadmodel.png" width="480" height="320">

For one jdek cut - 
>    1x face_plate,
>    1x base_plate,
>    6x mid_plate_stand_conn,
>    3x mid_plate_stand_base.

This also gives extra 2 stands but you will need extra mid plates for height. 

If you dont want extra stands then use "mid_plate_alone".

### CODE PART

As For the Code part you can follow this [Youtube tutorial](https://www.youtube.com/watch?v=OpIwI28cHpk) by Dustin Watts.
Just use the `User_Setup.h` provided or you can easy change the pin layout.

The mechanical switchs are controlled by Core0 on the rp2040 and its code recides in the first half of the ino file.

The LCD screen and touch part is handled by Core1 on the rp2040 so both the inputs works seamlessly together.
Also the functions and key binds for each key on the lcd can be changed in the second half of the ino file.

For the gifs some are preloaded in the `gifs` folder, with the program to make your own, (I dont know if I am allowed to 
share the program but I downloaded it for free so i dont think it will be an issue).


## Finished Look with my setup

<img src="/Images/2.jpg" width="480" height="320">


<img src="/Images/3.jpg" width="480" height="320">

### PCB Section (⚠️Warning⚠️ Not Checked)

You can find the source files and gerber files in PCB folder but be warned,
As I have not printed the PCB as it was expensive and went the route of hand wiring everything.

<img src="/Images/4.jpg" width="480" height="320"> <img src="/Images/5.jpg" width="480" height="320">

<img src="/Images/8.jpg" width="480" height="320"> <img src="/Images/9.jpg" width="480" height="320"> 
<img src="/Images/6.jpg" width="480" height="320"> <img src="/Images/7.jpg" width="480" height="320">
