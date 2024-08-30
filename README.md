This Arduino project uses LEDs to show how loud a sound is. As the sound level increases, more and more LEDs light up, creating a visual representation of the audio. 

How it works? 
The MAX9814 microphone captures ambient sound and sends this data to the Arduino. The Arduino processes the microphone data to determine sound intensity and controls 8 LEDs arranged in a specific order: 3 green LEDs represent low sound levels, 2 blue LEDs for medium levels, and 3 red LEDs for high levels. As the sound intensity increases, more LEDs light up, moving from green to red, providing a visual representation of the sound level. 

Components: 
MAX9814 Microphone: Picks up the sound waves. 
Arduino: Processes the microphone data and controls the LEDs. 
74HC595 Shift Register: Manages the 8 LEDs with minimal Arduino pins. 
8 LEDs: Display sound levels. 
