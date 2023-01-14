
# Automatic Plant Waterer

I created an automatic plant waterer to take care of my parents plants when they go away so I don't have to do it. It uses a capacitive moisture sensor which does not suffer from corrosion issues like a resisitive moisture sensor does. This project is my first embedded project on the STM32 platform. I used a STM32 Nucleo F401RE board. I coded the project using STMCubeIDE and the built in HAL, I would like re-code this in baremetal fashion in the future. 

## Circuit Diagram

![Moisture-Project](https://user-images.githubusercontent.com/45154810/212495954-17ed755d-dcbb-4f8c-9ff3-9eb800cd8f28.png)
I used an AC-DC wall adapter to create the 12V DC source which was then regulated down to 5V for the microcontroller and the moisture sensor. A logic level n-mosfet was used to control the water pump due to the high currents. A flyback diode was used to protect the circuit from backwards current when the electric magnetic field from the motor collapes.

## Demo Video

https://user-images.githubusercontent.com/45154810/212501898-389148e3-01c2-4a5f-9e6e-2b1555d6dc89.mov
