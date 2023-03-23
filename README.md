**Electromagnetic Ring Accelerator - This project is an educational and demonstration example of a particle accelerator. The layout allows you to see the approximate work of the particle accelerator.**

The main parts of the accelerator

The layout consists of two main parts, a circular track and a control part.

The control part is a box containing all boards from each boost solenoid. I made each replacement removable for carrying the layout, as well as in case of a need to quickly replace a faulty board with a new one.
The track for the ball in the form of a circle can be divided into four blocks. Each block has an electromagnetic coil made of copper winding wire with a cross section of 0.5 mm, a sensor (photoresistor), LED1 (needed for the correct operation of the sensor), LED2 (needed to monitor the state of the coil).
Description of the scheme

Photo relay - the photo relay consists of a photo resistor, a low-power transistor, a potentiometer (the potentiometer sets the sharpness and sensitivity of the sensor) and several resistors.
Switching transistor switch on IRFZ44N
Power relay of closing contacts of closing of coils
Note on the layout of the accelerator

The coil turn-on design uses contact relays only because I haven't found a way to keep the high-power transistor required from turning on when the coils are turned on. During the debugging of the circuit, I only broke one relay. It is necessary to select high-quality and proven relays or use solid state relays.
The accelerator requires 24V 2A DC voltage.
As an accelerated object, I took a metal ball with a diameter of 15mm. I managed to accelerate the ball to 2 m/s, the speed can be increased by reducing the diameter of the wire of the electromagnetic coil to 0.3 mm. and replacing the contact relay with a powerful MOSFET transistor.

https://oshwlab.com/artemakhmedkhan37/accelerator-4
![photo_2023-03-22_16-19-08](https://user-images.githubusercontent.com/128605523/227192974-04e02edd-34f5-4061-8cb7-e4cd0de47b25.jpg)
![photo_2023-03-22_21-01-17](https://user-images.githubusercontent.com/128605523/227192988-6889c7b1-22d0-433b-b1ac-fdf11b06040f.jpg)
![photo_2023-03-22_21-01-20](https://user-images.githubusercontent.com/128605523/227193012-cc068745-ac74-4219-a765-2d5911f4711f.jpg)
