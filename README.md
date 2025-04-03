# MARVEL-D-P
This is a detailed report on the MARVEL LEVEL 3 D&P Tasks. The tasks include the following.
### Mechanical Tasks
1) Assembly & Simulation
2) Computational Fluid Dynamics
3) Piston and crankshaft mechanism
4) Animation and rendering
5) Geometric Dimensioning and Tolerancing (GD&T)
6) Introduction to laser engraving
### Electronics Tasks.
1) Create A Voltage Multiplier
2) Create a circuit that provides short-circuit protection.
3) Colpitts Chaos
4) Complete the Simulink and Stateflow onRamp Course and get certified 

# MECHANICAL.
# 1)Assembly & Simulation
The tasks includes to design a robotic arm gripper using the Fusion 360 Software. The design parameters are in mm. This is a **Pneumatic Gripper** which is used in many industry scale applications.
![9pkdv4](https://github.com/user-attachments/assets/564ae23a-a2c3-421b-bc4b-54b2a3cfc41e)

# 2) Computational Fluid Dynamics
This task involves performing Computational fluid behaviour on the Airfoil we designed in the previous task. The environment which is used is air. The input velocity hitting the camber line is 50 m/s and the output is 0m/s. The airfoil chosen is NACA2414. 25 iterations have been successfully performed on the airfoil
![Screenshot 2025-04-02 133235](https://github.com/user-attachments/assets/6ea6ca27-6ab3-4498-96e6-36abbee99484)
![Screenshot 2025-04-02 134414](https://github.com/user-attachments/assets/43d2c7fc-bd16-49fd-be40-305b081d7eec)

# 3) Piston and crankshaft mechanism
This task we had to design a piston and a crankshaft mechanism which can run.The piston and crankshaft mechanism is a fundamental component of internal combustion engines, converting reciprocating (linear) motion into rotational motion. It consists of:
1)Piston – A cylindrical component that moves up and down inside the cylinder due to expanding gases from fuel combustion.
2)Connecting Rod – Links the piston to the crankshaft, transferring motion while allowing angular movement.
3)Crankshaft – A rotating shaft that converts the piston's linear motion into rotational motion, ultimately driving the vehicle's wheels or machinery
As the piston moves due to combustion, it pushes the connecting rod, which rotates the crankshaft in a continuous cycle. This mechanism is essential for engines in cars, motorcycles, and other machinery.
![Screenshot 2025-04-02 125743](https://github.com/user-attachments/assets/386cdc6e-bdf1-45da-bf39-663063773a75)

# 4)Animation and rendering. 
The tasks reqires us to design a **Lego Man** on fusion 360, assemble it and then render it into new environments. The 2nd task includes here is that we conduct a motion study on the joints and tweak it to make the **Lego Man** perform the movents of the joints of Lego man.
![9pke0m](https://github.com/user-attachments/assets/0bc487fb-8bb2-4150-ab2c-07894f211fe7)
![Screenshot 2025-04-02 141155](https://github.com/user-attachments/assets/2a4d4442-9b32-4835-9591-774c86609361)

# 5) Geometric Dimensioning and Tolerancing (GDnT)
GD&T, or Geometric Dimensioning and Tolerancing, is a standardized system using symbols on engineering drawings to define and communicate the acceptable variations in the geometry and dimensions of manufactured parts, ensuring they fit and function as intended
In Fusion 360, GD&T can be applied in 2D drawings using the Tolerance Feature. Users can assign geometric tolerances such as:

1)Form tolerances (Flatness, Straightness, Circularity, Cylindricity)
2)Orientation tolerances (Perpendicularity, Parallelism, Angularity)
3)Location tolerances (Position, Concentricity, Symmetry)
4)Profile tolerances (Profile of a Line, Profile of a Surface)
5)Runout tolerances (Circular Runout, Total Runout)
![Screenshot 2025-04-03 114306](https://github.com/user-attachments/assets/b00134dc-7cb1-43b0-b24b-173510cb45f1)

# 6) Introduction to laser engraving

Laser engraving is a precise and non-contact technique used to etch designs, text, or patterns onto materials by using a high-powered laser beam. The laser removes material by vaporizing the surface, creating permanent marks without physical wear.

### Key Features:
Works on metals, wood, glass, plastics, and leather.
Offers high accuracy and fine detailing.
No direct tool contact, reducing material damage.
Can be used for industrial marking, personalization, and artistic designs.
### Software for Laser Engraving Design
Several software programs are commonly used for designing and preparing files for laser engraving. These include:

###Vector & Graphic Design Software:
1)Adobe Illustrator – Ideal for creating detailed vector designs.
2)CorelDRAW – A popular choice for engraving professionals due to its powerful vector editing tools.
3)Inkscape – A free, open-source alternative for vector design.

### Laser Control & CAM Software:
1)LightBurn – A dedicated laser engraving software with design, editing, and machine control features.
2)LaserGRBL – A free and lightweight option for controlling GRBL-based laser engravers.
3)RDWorks – Used with Ruida controller-based laser machines, offering design and control features.
4)EZCAD – Commonly used for fiber laser engravers, especially for metal marking.

# Electronics Tasks
# 1)Create A Voltage Multiplier
This project aims to design a capacitor pump (charge pump) voltage multiplier using a 555 Timer IC as an oscillator. The goal is to increase a 9V input to 18V and then cascade it to 27V using a sequential charge-pump circuit. The design is implemented in TinkerCad for simulation and testing.

Circuit Explanation
### 555 Timer IC as an Oscillator
The 555 Timer is configured in astable mode to generate a square wave.
The frequency and duty cycle of the waveform are controlled using resistors and capacitors.
The generated pulse signal drives the capacitor pump stages.

### Charge Pump (Voltage Doubler & Tripler)
The circuit uses diodes and capacitors in a charge-pump configuration.
The first stage doubles the input (9V → 18V) using a voltage doubler circuit.
A second stage cascades the pump to triple the voltage (18V → 27V).

### Oscilloscope Readings
The waveforms on the oscilloscope confirm the oscillation of the 555 Timer and the stepped-up voltage levels at different stages.
![Screenshot 2025-04-01 214839](https://github.com/user-attachments/assets/efe9730b-e261-4fc3-a28c-fb1cbe7538f8)

# 2)  Colpitts Chaos
A Colpitts oscillator is a type of LC oscillator where the feedback network consists of a capacitive voltage divider and an inductor. The frequency of oscillation is determined by the LC tank circuit.
## Procedure
### Connect Components:
* Configure the capacitors and inductor in the feedback loop.
* Set up the op-amp in a non-inverting configuration.
* Provide a small initial voltage disturbance to kick-start oscillations.

### Run Simulation:
Set Transient Analysis for at least 10 ms.
Observe oscillations in the output waveform
![Colpits LC OSci (1)](https://github.com/user-attachments/assets/33afaae3-aef4-4746-bf3c-466dffb25c10)
![Colpits LC Osci (2)](https://github.com/user-attachments/assets/3dfd3fe3-8976-4527-a978-82c75c796e45)


# 3) Complete the Simulink and Stateflow onRamp Course
The MATLAB Simulink Onramp course is a free, interactive online course provided by MathWorks to introduce users to Simulink, a block diagram environment for modeling, simulating, and analyzing dynamic systems.
## Topics Covered:
!)Introduction to Simulink – Understanding the basics of block diagrams.
2)Building Models – Creating, configuring, and connecting blocks.
3)Simulating Systems – Running and analyzing simulations.
4)Using Scopes and Logs – Visualizing and interpreting simulation results.
5)Parameter Tuning – Adjusting model properties dynamically.
6)Subsystems and Hierarchy – Organizing models efficiently.
![Screenshot 2025-04-03 115622](https://github.com/user-attachments/assets/cd22b3b3-e15f-47d2-925b-9588579a4d9b)

# 4) Create a circuit that provides short-circuit protection.
This project involves designing a simple short-circuit protection circuit using a relay, LEDs, and a battery-powered motor system. The goal is to prevent damage to components by cutting off power in case of a short circuit.

### Circuit Explanation
1)Power Source: The circuit is powered by a 6V battery pack (four 1.5V AA batteries in series).

2)Relay (KS2E-M-DC5): The heart of the protection mechanism is a 5V relay, which acts as an automatic switch to disconnect the load in case of a short circuit.

3)Motor Load: A small DC motor is connected as the primary load.

### Indicators:

1)A red LED indicates a short-circuit condition.

2)A green LED signals normal operation.

3)Push Buttons: Used to control the relay mechanism, allowing for manual reset after a fault.

4)Connections: The relay coil is activated by the control circuit, and in case of a short circuit, the relay opens, disconnecting the motor and protecting the system.

This circuit provides a simple yet effective short-circuit protection mechanism by utilizing a relay to break the connection when an overcurrent situation occurs, preventing damage to components.
![Screenshot 2025-04-03 161411](https://github.com/user-attachments/assets/4be3dd90-8f8b-4103-8ae2-79bc38126f00)
![Screenshot 2025-04-03 161424](https://github.com/user-attachments/assets/e026b42d-1c83-4e55-9ee6-a3b02b2fc327)

