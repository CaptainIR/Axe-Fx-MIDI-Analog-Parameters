This project is for communication between AXE FX (in my case FM3, Untested on othe fractal projects) and Arduino UNO, Via MIDI. 
The code of this project is mostly of Nuts and Volts ( https://www.notesandvolts.com ). I just did sometinkering and ( i think added libraries ) , wanted to share there older project as i spent a long time trying to get a analog style amp controls to work with axe fx (amp face style controls). 
Credit Goes to Nuts and Volts for this code. I hope sharing this project will help others. 

I Currently have mine sett up to control Gain, Bass, Mid, and treble, this uses five pots for each parameter. 

Pot Wiring: 
lug 1 --> Goes to ground on arduino 
Lug 2 (middle lug) --> Goes to Analog input (A 1, 2, 3, 4, OR 5)
Lug 3 --> Goes to 5v On Arduino uno 

MIDI OUTPUT CONNECTION:
-Midi pin5 --> Goes to TX On Arduino
-Midi pin4 --> Goes to +5v On Arduino UNO
-Midi pin2 --> Goes to ground on arduino 

Heads Up: 
If this project does not work for you, use Arduino could IDE ( https://create.arduino.cc/edito ). Which is what I did as Arduino IDE was giving me errors, but arduino cloud ide worked right away. 
