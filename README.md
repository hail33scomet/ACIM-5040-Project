# ACIM-5040-Project
BCIT ACIM 5040 Variable Frequency Drive Project programmed with a Schneider Zelios Programmable Logic Relay and Allen-Bradley Powerflex 70 VFD (pump system).

The project involved filling a water tank up while making use of an automatic and manual mode. In automatic mode a telemecanique Ultrasonic sensor provided sensory analog feedback which was tuned via PI tuning to fill the tank to maintain a 70% full level. In manual mode the tank filled while pressing a button. The stop button purposely did not function in manual mode, but the Emergency DC braking function did. Three pilot lights signified when the system was ready (flashing), running (solid), and when the VFD faulted during E-braking.
