**LED On-Off Simultaneous Control Using 8 LEDs**
This project showcases the use of a microcontroller (Arduino/ESP) to control 8 LEDs simultaneously in a specific pattern — such as turning all LEDs on and off together, or with custom delays and effects. It demonstrates the basic understanding of digital output control, pin configuration, and synchronized LED behavior, making it ideal for embedded system beginners or testing digital I/O logic.

🔑 Key Highlights
Component Used: 8 x LEDs
Microcontroller: Arduino Uno / Nano / ESP8266 / ESP32
Power Supply: USB or 5V external
Programming Language: C / Arduino IDE
Output: Synchronized LED blink pattern

🛠️ Technologies & Tools
Arduino IDE
Digital Output Control
GPIO configuration
Optional: Breadboard for prototyping

⚙️ Functional Flow
All 8 LEDs are connected to digital GPIO pins.
The microcontroller sets all pins HIGH (turns LEDs on) or LOW (turns them off) at the same time.
Delay intervals define the blinking speed or pattern behavior.
Can be extended to patterns like wave, chase, or flashing groups.

🎯 Learning Outcomes
Configuring multiple GPIO pins for digital output
Basic understanding of loops and delays in embedded code
Synchronized output control
LED circuit design and prototyping

🚀 Future Enhancements
Add push button to toggle between patterns
Add PWM control for brightness
Extend to 16 LEDs using shift registers (e.g., 74HC595)
Create LED animations or wave effects
