## About Me
I am a senior in high school and I've been playing with circuits for as long as I can remember. I am into embedded hardware, power electronics, lasers, and FPV drones. I also enjoy chemistry, baking, and running.

## Projects I'm Working On

### Sol
A solar-powered RC plane that can fly indefinitely (until the batteries degrade severely). This is a huge project and is a culmination of all my work and experience so far. It is a group project—my friends are working on the structure and aerodynamics while I am handling the avionics (the electronics that fly the plane). A lot of the work involves carefully setting up a Pixhawk 4 flight controller running PX4 along with several peripherals, but Sol also requires a custom power management board which I am currently designing. Additionally, the ESC on Sol will be a custom variant of SinESC (see below), optimized to perform well at low motor currents.

### SinESC
A modern ESC for FPV drones that is significantly more efficient than standard BLHeli_32 ESCs. I got into FPV several years ago to satisfy my general affinity for things that fly, and I wanted to use my electronics and PCB design skills to improve the hobby rather than just buying pre-made parts (which got boring pretty quickly). I started looking at ways to increase flight times, and learned that the ESCs everyone uses employ a simple but inefficient drive technique. I decided to bring Field-Oriented Control (FOC) to the hobby, and that's when I created SinESC. If you want the details regarding how SinESC differs from other ESCs, the repository is below. Otherwise, just know that the whole point of SinESC is to improve efficiency and smoothness, both of which are extremely important to any pilot.

### Universal Laser Driver
Solves the problem of having to correctly match batteries, laser drivers, and diodes based on input and output voltage requirements. Intended for low-power laser pointers where space is minimal. Especially well suited for builds utilizing the Leadlight Pen Host, because the PCB is designed to fit in the plastic carrier that normally holds the switch board. The Leadlight Pen Host requires two 10440-sized battery cells, and the Universal Laser Driver allows the user to swap between AAA alkaline and 10440 lithium-ion cells without worrying about damaging the driver or insufficient voltage to power the diode. This project was the result of my own frustrations while trying to build a laser as a gift to someone.
