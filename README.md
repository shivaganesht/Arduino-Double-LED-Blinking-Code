# Arduino-Double-LED-Blinking-Code


This Arduino project demonstrates the basic functionality of blinking two LEDs alternately using the Arduino IDE. Both LEDs blink on and off with a one-second interval.

## Installation

1. Clone this repository to your local machine using `git clone https://github.com/shivaganesht/Arduino-Double-LED-Blinking-Code.git`.
2. Open the project in the Arduino IDE.

## Circuit Connections and Reference Diagram

Connect two LEDs to the Arduino board as follows:

![2 LED Blinking](https://github.com/shivaganesht/Arduino-Double-LED-Blinking-Code/assets/69391183/2b6f059c-6afd-4dfd-b12e-5a29688eabe1)

- Connect one leg of the first LED to pin 13 on the Arduino board.
- Connect the other leg of the first LED to ground (GND) on the Arduino board.
- Connect one leg of the second LED to pin 12 on the Arduino board.
- Connect the other leg of the second LED to ground (GND) on the Arduino board.

## Usage

1. Connect your Arduino board to your computer.
2. Upload the code to your Arduino board. If you're unsure how to upload code to your Arduino board, refer to the [Arduino documentation](https://www.arduino.cc/en/Guide/HomePage).
3. Both LEDs will start blinking alternately with a one-second interval.

## Code Overview

```cpp
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT); // Set the built-in LED pin as an output
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH); // Turn the LED on
  delay(1000); // Wait for one second
  digitalWrite(LED_BUILTIN, LOW); // Turn the LED off
  delay(1000); // Wait for one second
}
```

## Conclusion

This project provides a simple example of blinking two LEDs alternately with Arduino. Feel free to modify the code and experiment with different blinking patterns!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
