# rgb-led-sketch

Quite simple arduino sketch for blinking rgb led via serial port.
Designed for [karma-led-reporter][0]

## Usage

1. Connect RGB LED to arduino: Red - pin 3, Green - pin 5, Blue - pin 6, Cathode - GND. Dont forget about current limiting resistors.

2. Connect 120 ohm resistor between RST and 5V pins to prevent reset after each serial connection.

3. Upload rgb-led-sketch.ino to board.

4. Send `0,255,0` string via serial monitor for testing.

## License

rgb-led-sketch is licensed under the [MIT License][1].

  [0]: https://github.com/val-/karma-led-reporter
  [1]: http://opensource.org/licenses/MIT
