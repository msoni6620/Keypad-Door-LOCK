# KEYPAD_DOOR_LOCK <BR>
***Made by :MAYANK SONI ***
***Date : 12/12/2018***
The project involves using an ESP32 microcontroller, a 4x4 keypad, and an electromagnetic lock to create a secure door lock system that requires a password for access. The system allows users to set and enter passwords to lock and unlock doors. If the correct password is entered, the ESP32 controls the electromagnetic lock to unlock the door. <br>

# Key features and components include: <br>
**ESP32 microcontroller:** Serves as the main controller, processing user input from the keypad and controlling the lock mechanism. <br>
**4x4 keypad:** Used for entering passwords and interacting with the system. <br>
**Electromagnetic lock:** Locks and unlocks the door based on the entered password under the control of the ESP32. <br>
**LCD display (optional):** Can be added to display system status, password prompts, and error messages <br>


The system is programmed using the *Arduino IDE* and *C++*. The password is stored in the ESP32's non-volatile memory (EEPROM) to persist across power cycles. The keypad is interfaced with the ESP32 using a matrix-style connection, and the microcontroller scans the keypad to detect key presses and process the entered password.<br>
By combining the ESP32's processing power, the keypad for user input, and the electromagnetic lock for door control, this project creates a robust and secure password-based door lock system. <br>