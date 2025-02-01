# Welcome to JDEK
## An open source macropad with <br> 30 buttons and programmable 3.5 inch touch lcd display

<img src="/Imgaes/1.png" width="480" height="320">

There are two main folders for Code and CAD files.

CAD files were created in Fusion and are intended to be laser cut.

I hade 3mm clear acrylic sheet in mind when designing.

If you want thicker you will need to thicken the slots in the stand base 
or just cut thicker face and base plates and 3mm mid plates. 


<img src="cadmodel.png" width="480" height="320">

For one jdek cut - 
    1x face_plate,
    1x base_plate,
    6x mid_plate_stand_conn,
    3x mid_plate_stand_base.

This also gives extra 2 stands but you will need extra mid plates for height. 

If you dont want extra stands then use "mid_plate_alone".


As For the Code part you can follow this [Youtube tutorial](https://www.youtube.com/watch?v=OpIwI28cHpk) by Dustin Watts.

Just use the `User_Setup.h` provided or you can easy change the pin layout.

The mechanical switchs are controlled by Core0 on the rp2040 and its code recides in the first half of the ino file.

The LCD screen and touch part is handled by Core1 on the rp2040 so both the inputs works seamlessly together.

Also the functions and key binds for each key on the lcd can be changed in the second half of the ino file.

For the gifs some are preloaded in the `gifs` folder, with the programme to make your own, (I dont know if I am allowed to 
share the programme but I downloaded it for free so i dont think it will be an issue).


## Finished Look with my setup

<img src="/Imgaes/2.png" width="480" height="320">


<img src="/Imgaes/3.png" width="480" height="320">
