Name:Mariha Iftikhar
Reg no:23-NTU-CS-1045
pin map for task B:
/*
buttonPin  → GPIO 32   (Input, single push button with INPUT_PULLUP)
ledPin     → GPIO 16   (Output, controls the LED)
buzzerPin  → GPIO 17   (Output, controls the buzzer)
OLED Display (I2C Connection):
   SDA → GPIO 21
   SCL → GPIO 22
   I2C Address: 0x3C
   Resolution: 128x64 pixels
- Short Press (less than 1.5 seconds):
    → Toggles the LED ON and OFF.
    → OLED displays “LED ON” or “LED OFF”.

- Long Press (greater than 1.5 seconds):
    → Activates the buzzer while the button is held.
    → OLED displays “BUZZER”.
    → Stops when the button is released, showing “Stopped”.

- Button uses internal pull-up resistor (LOW = pressed, HIGH = released).
- Debounce delay of 50 ms is used to avoid false triggering.
*/
link:
https://wokwi.com/projects/445850113932143617

