# Piano
Piano Playing Bot is a robot which replicates the mechanism by which a human being plays piano. In this bot **3D printed** hand like structures are used to replicate the motion of human fingers over the keys of piano.**Solenoid valves** are used for the movement of fingers where as **Stepper motors** are used for motion of hand.
## Pre Requisites
### Softwares
1. FL-Studio:Basic knowledge of FL studio and midi file is required in order to get the information of chords and duration of playing of chords.
2. Arduino:Knowledge is required to verify working of different components as well as giving instructions for running the complete setup.
### Components used

1. Mechanical-
   1. 1 Wooden Boards- For setting the base for Piano System.
   2. 10 Finger like 3D Printed Structures( They should contain a 6 mm hole at the centre of them.).
   3. 2 3D Printed Cup like structure(Used to create hand like structure for fingers).
   4. 2 15 cm steel rods of diameter 2.5 mm each.
   5. 2 Sliders(For the movement of cup like structure).
   6. Long Wooden Blocks
   7. 4 mm Screws
   8. Drill Machine with 4 mm Drill bit
   9. Hammer, Saw, Electrical Tape,Plier etc.
   10. A few Nails,Glue Gun
   11. 2 pair of Rack and Pinion
   12. Aluminium Channels(Square and L )
2. Electronics-
   1. 2 Stepper Motors (10 KG Torque preferred).
   2. 1 Arduino MEGA 2560
   3. 10 Solenoid Valves( 12 V DC each) .
   4. 2 Motor Drivers (For running Stepper Motors)
   5. 10 Relay Switches. (For ON and OFF control of Solenoids).
   6. Heat Sink
   7. ULN 2003-For controlling the voltages in Relay Switches. 
   8. 12 V/5A Adapter- For power supply.
   9. Breadboards and plenty of jumpers.(Male to Male,Male to Female,Female to Female)
   10. Digital Multi Meter
   11. Switches
 ### Importance of various components
 
1. **Stepper Motor** :A stepper motor is a brushless electric DC motor that divides a full rotation into a number of equal steps. The motor's position can then be commanded to move and hold at one of these steps without any feedback sensor, as long as the motor is carefully sized to the application in respect to torque and speed.
It is used to control the pressure of air coming from vacuum cleaner blown into the flute.
2. **Arduino** :Arduino is an open source, computer hardware and software company, project, and user community that designs and manufactures single-board microcontrollers and microcontroller kits for building digital devices and interactive objects that can sense and control objects in the physical world.  
3. **Solenoid Valves** : A solenoid valve is an electromechanical controlled valve. The valve features a solenoid, which is an electric coil with a movable ferromagnetic core in its centre. This core is called the plunger. In rest position, the plunger closes off a small orifice. An electric current through the coil creates a magnetic field. The magnetic field exerts a force on the plunger. As a result, the plunger is pulled toward the centre of the coil so that the orifice opens. This is the basic principle that is used to open and close solenoid valves.
4. **Relay Switches** : Relays are switches that open and close circuits electromechanically or electronically. Relays control one electrical circuit by opening and closing contacts in another circuit. As relay diagrams show, when a relay contact is normally open (NO), there is an open contact when the relay is not energized. When a relay contact is Normally Closed (NC), there is a closed contact when the relay is not energized. In either case, applying electrical current to the contacts will change their state. 
5. **Motor Drivers** : A motor driver is a little current amplifier; the function of motor drivers is to take a low-current control signal and then turn it into a higher-current signal that can drive a motor.
## Design and Control :
 First of all mount keyboard on the big wooden board, so that it does not get displaced from its position. Take the measurements of keys and 3D print the Cup like structure with the 6 mm holes on its sides (You can see in the pictures) such that it can cover 5 consecutive keys. Now 3D print the finger like structures with 6 mm holes at the center of them. Now place 5 fingers inside one cup and insert the 5 mm rod through all the fingers across both the holes of the cup. Now place all keys at an appropriate distance from each other, such that they cover one key each(You can use Tape to create distance or something which doesn't allow them to move from their place, but make sure they are free to rotate). Place this entire structure on a Slider such that it is able to slide with the slider. Stick all the solenoids on the back of this structure such that when current is passed through them, they push the fingers and the key is pressed (Seesaw mechanism). Attach pinion to the shafts of Stepper Motors. Attach the rack to the movable part of sliders. Mount each stepper on either side of the keyboard and mount the slider using wooden blocks such that the rack and pinion work smoothly and all the keys are pressed properly.
  
   Make the circuits using relays and ULN such that each relay controls a solenoid.Connect all solenoids to relay so that relay work as a switch.Use motor drivers to drive the steppers.Male all connections to Arduino Mega.Power the circuits using 12V/5A adapters.Upload the files to Arduino and you are ready to rock.
   
   **For Software related details read the Readme.md file in parent folder.**
   ## Inference: 
   This is just one way of making a robotic keyboard.We also tried other ways like playing using servo motors, but servo motors are not as fast as solenoid valves and present some serious delays.Although we can produce similar(to the black keys) sounds using all the white keys but we are still working on the mechanism of playing the black keys. Enjoy the melodies till then.
