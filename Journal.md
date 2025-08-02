**Total Time Spent: 19.5 Hours**

7/27/2025

**Time Spent: 7 Hours**

As an introduction to both hardware and 3D printing, the initial step was to consider the Different 3D printers. Comparing the Delta, CoreXY, and bed slinger design, I opted for the bed slinger due to it being easy and because it's safe and easy as an entry construction.

My first thought was low cost and high accuracy. The choice of equipping all axes (X, Y, and Z) with V-slot rails kept cost and modularity as advantages. To smoothly and continuously move the Z-axis vertically, I supported the V-slot rails with a lead screw actuator.

In the case of the extruder, I opted for the direct drive X-carrige system and matched it up alongside an E3D V6 Volcano hotend, both of them being inexpensive yet good enough for me. I also incorporated a proximity sensor so as to allow automatic bed leveling.

Print size was set to 300×300×350 mm, and this will suit most of the applications that I intend doing with this machine. Control board was chosen as being a BIGTREETECH SKR MINI E3 V3.0 because of proper documentations, an affordable cost, and Klipper compatibility. From local prices, the cost of constructing this machine came to approximately $325 USD.

![part of searching Notes](img/notes.png)

7/28/2025

**Time Spent: 3 Hours**

I began designing in fusion 360 and it was my first time to use it so the progress like to be delayed. I designed the frame of the 3d printer of the aluminum extrusions with length of 420x640x600 mm I used 2040 aluminum V-slot extrusions for additional rigidity (frame) . I used a combination of corner brackets and T-plates to strengthen the joints, particularly on the X-axis which supports the print head and moves frequently.

![frame](img/frame.png)

7/29/2025

**Time Spent: 1 Hours**

I designed a custom mechanical endstop triggered by the linear rail carriage, I designed two different ones one for x-axis to control the print head and another one to the y axis for the bed mount.
I found that the mount bed in egypt is not avaliable with good quality and so expensive so I decided to design it and use acrylic sheet of 4 mm thickness and cut it by the cnc router.

![end stop1](img/endstop1.png)
![end stop2](img/endstop2.png)

![mount bed](img/mountbed.png)

7/30/2025

**Time Spent: 2 Hours**

I have made the y-axis and added to the mount bed 12 V-wheel and it connected to a belt that is move by motion of the stepper motor. I also added spacers to make the 3d printer stand on it.

![y-axis](img/y_axis.png)

7/31/2025

**Time Spent: 4 Hours**

I also completed the entire Z-axis design using custom 3D-designed plates instead of use of univeral plates and motor aliminuim mounts as it is more expensive and heavier. then optimized for 3D construction, light weight yet with integrity.

There are lead screw and V-slot rails for Z-motion and there is also proper alignment for Z-axis to reduce wobble. The design does accommodate fairly heavy weight of the print head but does not affect the stability.
there is a side of plates that holds the end stop and the stepper motor that will bring the filament to the print head. the other side just used for the motion.

![z-axis](img/z_axis.png)
![left side](img/left_side.png)

![3d printed](img/3d_printed.png)
![acrlyic parts](img/acrylic.png)

8/1/2025

**Time Spent: 3 Hours**

I finalized the X-axis and print head assembly. The direct-drive extruder, Volcano hotend, and proximity sensor were mounted. I also added belt clamps and tensioners for the X-axis motion system. Final adjustments ensured correct alignment between the nozzle and the center of the print bed.
and added a support from the higher point in the extrusions to increase rigidity and durability.

![print head](img/print_head.png)

![Final](img/printer.png)

