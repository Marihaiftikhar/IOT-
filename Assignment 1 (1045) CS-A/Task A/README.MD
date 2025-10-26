Name:Mariha Iftikhar
Reg no:23-NTU-CS-1045
pin map for task A:
/*
LED1  → GPIO 16   (Output)
LED2  → GPIO 17   (Output)
LED3  → GPIO 18   (Output)
BTN_MODE  → GPIO 32   (Input, used to change modes)
BTN_RESET → GPIO 33   (Input, used to reset to mode 0)
OLED Display (I2C):
   SDA → GPIO 21
   SCL → GPIO 22
   I2C Address: 0x3C
   Resolution: 128x64 pixels
Mode 0 → All LEDs OFF
Mode 1 → Alternate Blink (LED1 → LED2 → LED3)
Mode 2 → All LEDs ON
Mode 3 → PWM Fade (all LEDs fade in/out together)

Button Functions:
- MODE button cycles through all modes.
- RESET button resets system back to Mode 0 (All OFF).
*/
link:
https://wokwi.com/projects/445875491259994113







