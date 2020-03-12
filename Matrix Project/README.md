# FLAPPY BIT

**How to play**: Just press the button fast and avoid the pipes! Go as far as you can!  
***Warning!!!***: It's hard!

**Gameplay**: https://www.youtube.com/watch?v=yjZTo2Qcby8

**Hardware**: 
- Arduino UNO
- Wires
- 8x8 LED matrix
- LCD
- Joystick
- MAX7219 Driver
- Potentiometer

**Features**:

1) Score <- if you pass a pipe, you score increases
2) Progress in difficulty <- speed increases + decrease space between pipes + space between 2 neighbour pipes
3) More lives <- 3 lives
4) Levels <- when you pass 10 pipes, then the difficulty increases
    - Level 1: Speed - slow  |  Space - 3  |  Distance - far 
    - Level 2: Speed - slow  |  Space - 2  |  Distance - far
    - Level 3: Speed - medium  |  Space - 3  |  Distance - far
    - Level 4: Speed - fast  |  Space - 3  |  Distance - far
    - Level 5: Speed - very slow  |  Space - 3  |  Distance - tiny
    - Level 6: Speed - slow  |  Space - 3  |  Distance - tiny
    - Level 7: Speed - slow  |  Space - 3/2  |  Distance - tiny  
    
    (Speed = Bit's speed | Space = space between pipes | Distance = distance between 2 neighbour pipes)
    
5) Level choose <- can start with any level
6) Name <- name can be introduced via Arduino's Serial.read()
7) Animations <- GAME OVER!
8) Highscore <- highscore and player name saved on EEPROM

![alt text](https://github.com/Mickai55/Introduction-to-Robotics/blob/master/Matrix%20Project/Game%20Picture.jpeg)
