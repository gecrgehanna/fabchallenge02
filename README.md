# fabchallenge02 - ZOETROPE PUZZLE

<img src="/zoetrope diagram copy-02-min.png" width ="100%">

## IDEATION

### INITIAL IDEA + CONCEPT

Our group is formed of 3 members: George, Kai and Ruben. We have already formed previous alliances as duos given our underlying interests in biomaterials mainly, but also toys and electronics.

We have decided to use this collaboration to create yet another artifact in our toy collection, and we ended up deciding on making a zoetrope, but giving it a more custom/DIY approach.

### PURPOSE

Our zoetrope, is supposed to present 12-frame animations using a strobe light and a rotating disk where the singular “frames” of animation can be attached.

From a toy mindset, the zoetrope could also serve as a puzzle that requires the player to find the correct order of the singular pieces in order to make the animation continuous.

### PLANNING

We had a more or less clear way to execute the artifact, taking into considerations the different steps of the process that would need to be assembled eventually.

*First day* was dedicated to identify the concept and start sketching out our animation frames.

*Second day* is dedicated to start working with the mechanisms (motor, strobe light, rotating disk, holes and joints). Also, finalizing the animation frames.

*Third day* is to finalize the mechanisms and test out the rotation of the disk and how it works with out circuit, and to finalize the execution of the animation frames.

*Fourth day* is for tuning, synchronizing the artifact, and documenting.

### DIAGRAM

<img src="/zoetrope diagram copy-01-min.png" width ="100%">

### INTEGRATED DESIGN

The artifact is made out of 3 main parts, all inter-conncted with each other. We will explain from top to bottom each part.

#### FIRST PART: FIGURES

The single pieces (aka frames) that make up the whole animations. These pieces can be 3d-printed, laser cut or molded, as long as they fit perfect in the holes (6mm diameter) of the disk and wouldn’t fly off when the disk is rotating.

The nice part about these pieces is that they can be replaced with different sets that can be designed and fabricated.

#### SECOND PART: DISK

The disk is a circular wooden piece, with 12 holes around the edge of it to fit each figure, and a hole in the middle that would allow the connection to the lower electronic part of the artifact.

#### THIRD PART: CIRCUIT

Finally, the circuit consists of a motor and a light (that has strong exposure and that can be manipulated into flashing on and off). These are pieced together and connected to a power source, all hidden inside the basic square box on which the disk is mounted.

### HONEST DESIGN

For this project, we used CNC, a laser cutter, a 3d printer, and some electronic circuits. We assigned every component of the project to be made with the most efficient medium that it can be made with. For example, the disk has to be sturdy so it’s strictly done with the CNC. However, the figurines could be both laser cut, 3d printed or manually molded.

Finally, the whole artifact wouldn’t work without the electronic board, which connected the light source, the motor and a small rotating knob to be able to control the speed of the light flashes manually, all connected and manipulated through Arduino.

### SOLUTIONS

Firstly, we tried to 3d print the little figurines that were to be inserted in the disk holes, however, we realized that it was a time consuming process that wouldn’t really allow us to experiment with other shapes and figures. Which is why we resorted to laser cutting as we could be more efficient with out experimentation.

### DESIGN BOUNDARIES

Initially, we would have preferred to 3d print more volumetric figures, but we were restricted with the time and our design capabilities that would allow us to produce a continuous flow of animation and freeze the frames we need from it. Not to mention that the 3d printing really takes time, and wouldn’t allow us to test the functionality.  Other than that, we had some issues with the 3d component piece that connects the motor to the disk. As much as we tried to measure and create tolerance for the holes to fit properly, we still had some trouble assembling.  This was specifically hard due to the necessity of having the rotational movement completely balanced and horizontal; any little flaw in the contact and assembly can produce an angle we wouldn’t want that would ruin the animation flow. 

### FUTURE OPPORTUNITIES

This project joins our collaborative list of toys made for emergent contexts. Some potential future directions for it would definitely be creating more sets of figurines that way things can replaced and the artifact used to its fullest.  Another idea would be to experiment with different materials, maybe attempting to mold the figures out of biomaterials could be an idea.  We would also like to work on the packaging of the whole object and hopefully being able to produce it as an enjoyable toy, but more importantly helping parents build it.

## REPLICABILITY

### FABRICATION + BOM

#### MATERIALS USED:

• PLYWOOD 9mm
• MDF 2.5mm
• ESP32
• Motor 5V DC
• Light 700 mA, LED

#### TECHNOLOGIES USED:

• CNC
• Laser Cutter
• 3D Printer
• Arduino

*step 1*
Cutting the Disk with CNC.

*step 2*
Laser cut / 3d print / manually sculpt / mold and cast the design of the figures.
P.S: They have to be 12 pieces that make an animation when put together, 5 cm tall, with joints at the bottom that are 9mm (height) and 6mm (thickness).

*step 3*
3D print the connecting piece.

*step 4*
Connect the circuit using the Motor, solder the circuit complete. And then attach the motor to the hole in the 3d adapter piece, which should be inserted in the disk central hole.

*step 5*
Using Arduino and the knob mounted on the circuit, adjust the flash rate to the speed of the motor in a way that would create a flowy harmonious animation.

### DESIGN FILES

Find them here.

### ITERATION PROCESS + PROBLEMS

The initial idea was to make a controllable lamp, which slowly turned into a flashing object/toy and then we discovered zoetropes and the possibility of them being in 3D. We tested several ways to produce the figurines, we tried 3d printing them, however they were too thin given our scale.

We also had a hard time with the 3d printed piece, attempting different type of joints between the motor and the disk before we finally got it right.

### FINAL PRODUCT PHOTOS
