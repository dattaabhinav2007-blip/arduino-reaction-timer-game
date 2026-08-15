# arduino-reaction-timer-game
An Arduino UNO reaction timer game that measures how quickly a user presses a button after an LED turns ON. The project uses millis(), random delays, push button input, and LED output to calculate and display reaction time in milliseconds on the Serial Monitor.

Arduino Reaction Timer Game

This project is a simple Reaction Timer Game made using an Arduino UNO, an LED, and a push button. The idea is very simple: after a random delay, the LED turns ON, and the user has to press the button as quickly as possible. The Arduino then calculates how fast the button was pressed and shows the reaction time on the Serial Monitor.

I made this project to practice timing and program logic in Arduino. It helped me understand how "millis()" works and why it is useful for measuring time without depending only on "delay()". I also got more practice with button input, LED control, and writing cleaner Arduino code.

What this project does

- Waits for a random time between 2 and 5 seconds
- Turns ON the LED
- Starts a timer
- Detects when the button is pressed
- Calculates the reaction time
- Displays the result in milliseconds on the Serial Monitor

Components Used

- Arduino UNO
- LED
- 220Ω Resistor
- Push Button
- Breadboard
- Jumper Wires

How it works

1. The LED stays OFF at the beginning.
2. Arduino waits for a random amount of time.
3. The LED turns ON.
4. The user presses the button.
5. Arduino measures the time between the LED turning ON and the button press.
6. The reaction time is shown on the Serial Monitor.

This is one of the projects from my Arduino learning journey, and it gave me a better understanding of timing and simple embedded programming logic.
