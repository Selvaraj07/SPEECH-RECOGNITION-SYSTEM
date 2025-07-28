# SPEECH-RECOGNITION-SYSTEM

COMPANY: CODTECH IT SOLUTIONS

NAME: SELVARAJ P

INTERN ID: CT04DH870

DOMAIN: EMBEDDED SYSTEMS

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH
OUTPUT <img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/81cf585f-3065-4e95-a586-9223b7fb8e7f" />
DESCRIPTION: This internship task focuses on creating a basic LED control system using Arduino Uno and serial communication. The goal is to allow a user to turn an LED ON or OFF by sending commands through the Serial Monitor. This project introduces a fundamental concept in embedded systems—digital output control through serial input.

The hardware setup is simple and consists of a single LED connected to digital pin 13 of the Arduino, in series with a current-limiting resistor. The Arduino listens for serial input (like "1" to turn ON and "0" to turn OFF the LED) and executes the appropriate action, displaying feedback in the Serial Monitor for user confirmation.

CODE DESCRIPTION: The code begins by defining the LED pin and initializing it as an output in the setup() function. Serial communication is started using Serial.begin(9600). Inside the loop(), the Arduino checks for any incoming serial data using Serial.available().

It reads the command using Serial.readStringUntil('\n'), trims whitespace, and then compares the input string. If the input is "1", the LED is turned ON and a message is printed. If the input is "0", the LED is turned OFF. For any other command, an "Unknown command" message is printed, ensuring clear interaction with the user.

APPLICATION: This project serves as a foundation for building more complex input/output systems using Arduino. It teaches essential concepts of serial communication, input parsing, and hardware control, and can be adapted to control multiple devices.
