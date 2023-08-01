# Arduino Calculator

This Arduino calculator code enables you to build a simple calculator using an Arduino board, a 4x4 matrix keypad, and a 16x2 LCD display. The calculator supports basic arithmetic operations, including addition, subtraction, multiplication, and division.

## Hardware Requirements

To create this calculator, you will need the following components:

- Arduino board
- 4x4 matrix keypad
- 16x2 LCD display
- Potentiometer for LCD contrast adjustment

## Circuit Diagram

Please refer to the circuit diagram given in repository for the connections requrired.

## Getting Started

1. Clone or download this repository to your local machine.
2. Connect the hardware components as per the circuit diagram.
3. Upload the `calculator.ino` file to your Arduino board using the Arduino IDE.
4. Power on your Arduino board and the calculator circuit.

## Usage

1. Upon powering on, the LCD will briefly display "GoodArduinoCode Calculator" as a splash screen.
2. The calculator is now ready to receive input, and the LCD will display a blinking cursor.
3. Use the 4x4 number pad to enter numbers and arithmetic operators (+, -, *, /).
4. Press "=" to calculate the result. The LCD will display the answer.
5. To clear the input or start a new calculation, press an arithmetic operator (+, -, *, /).

## Notes

- You can enter negative numbers by pressing "-" as the first input.
- The calculator can handle decimal numbers, but each number can have only one decimal point.
- The cursor on the LCD blinks every 0.5 seconds to indicate input readiness.
