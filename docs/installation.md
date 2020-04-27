## Installation
---
1. `git clone https://github.com/COVID-19-electronic-health-system/PanFLUte.git`
2. `cd PanFLUte/board`
3. `./install.sh` 
4. Now all the required dependency are installed. 
## Programming 
---
The microcontroller architecture used is Atmel’s [AVR](https://en.wikipedia.org/wiki/AVR_microcontrollers). Most of the AVR chips are programmed via ISP (In-system programming) which the PanFLUte is with.
To flash the firmware first you insure power is running to the board by plugging in the micro-B USB. 
Next you must hookup an ISP programmer to the ISP header pins on the PanFLUte board. 

1. Inside the *board* directory run `make` to build the firmware. 
2. `make flash`