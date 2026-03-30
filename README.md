# FPGA-Tilt-Meter-Display-Rotator
This project uses an onboard accelerometer, ADXL362, on the Nexys A7 100T FPGA board to determine device tilt and orientation and provide real-time visual feedback.
The project-
Gets the accelerometer data from the Nexys A7 100T board using SPI protocol.
Calculates Roll and Pitch angle from the data using fixed point CORDIC algorithm.
Rotates a special character(∩) in seven segment display according to the Roll angle.
Shows different levels on LEDs according to the Pitch angle magnitude as the board is tilted.

Input: Read full X, Y, Z acceleration data.
Output: Display a fixed character that rotates (∩) based on roll angle thresholds. Use 8 onboard LEDs as a digital spirit level indicating the magnitude of the pitch angle (forward/backward tilt).


YouTube Link - https://youtu.be/dHNygxtZgfk?si=oNPCj8PKV25jcnPz

