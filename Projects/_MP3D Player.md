I wanted to make my own MP3 player from small electronics and 3D print body for it. Heavily based on 3D render: [pinterest link](https://pin.it/7sLObrf5z).

### Components:
- ESP32: The brain. It handles the logic, UI on OLED and commands the DFPlayer.
- DFPlayer Mini: Decodes the MP3 files from microSD card.
- OLED (SSD1306): Displays track numbers, volume...
- Rotary encoder: Dedicated volume control with 3D printed knob.
- 3 switches: Play/Pause, Next, Previous track.
- For future 360 Servo: will rotate pencils when the ESP32 detects the player is in "PLAY" state.

Work:
Right now I'm waiting for female mini jack slot. After I get it I'll test the circut and ESP code since it'd be cool to actually hear if it plays music correctly. %% Holding onto wires to male jack of headphones is hard and annoying %%

## V1.3
Print quality was ASS. Need to make it print on flat surface not at an angle. Idea is to do print it on face and add the bottom wider part as assembly. Steal the idea from "Gigantic Audio Cassette Tape w Optional Lightbox"

### V2.1
Need to make pegs smaller or holes bigger. Also the main peg system needs change since if they are in the corners with hard corners they don't wanna fit right in and are prone to brake. It's for both the big and small parts of the cassette. 
Also there is missing hole for cables of oled screen. And the block holding it in needs to be a little higher. 
Beside that cassette looks pretty good. We need to think about connecting it to the main box - and of course start to project it. 

### V2.2
All seems ok. But all wholes and pegs needs to be bigger - they break when going in and print poorly.
Can add extra block for oled.