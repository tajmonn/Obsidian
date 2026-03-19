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