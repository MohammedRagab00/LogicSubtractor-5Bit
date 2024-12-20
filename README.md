# 5-Bit Binary Subtractor with 7-Segment Display and Hex Digit Display

## Overview
This project implements a 5-bit binary subtractor using Logisim, a digital circuit simulator. The subtractor supports both decimal and hexadecimal representations for the operands and the result. The circuit also accounts for negative results, displaying the negative sign when the second operand is greater than the first.

## Features
- **5-Bit Binary Subtractor**: Performs subtraction between two 5-bit binary numbers.
- **7-Segment Display**: Displays the values of the operands and the result.
- **Control Bit**: Switches between decimal and hexadecimal representation for operands and results.
- **Negative Sign Handling**: Displays a negative sign if the result of subtraction is negative.

## Requirements
- [Logisim](https://github.com/logisim-evolution/logisim-evolution): Digital circuit simulation software.

## Circuit Design
### Components Used
1. **5-Bit Binary Subtractor**: Implements the subtraction logic for two 5-bit binary numbers.
2. **7-Segment Decoder**: Converts binary output into decimal or hexadecimal format for display.
3. **Control Bit Logic**: Handles switching between decimal and hexadecimal representations.
4. **Sign Display Logic**: Adds a negative sign for negative results.

### Logic Flow
1. Input two 5-bit binary operands.
2. Perform subtraction using a 5-bit subtractor.
3. Check if the result is negative and handle the sign accordingly.
4. Use the control bit to determine the output format (decimal or hexadecimal).
5. Display the operands and result on 7-segment displays.

## How to Use
1. Open the Logisim file.
2. Input two 5-bit binary numbers.
3. Set the control bit:
   - `0`: Display operands and result in decimal.
   - `1`: Display operands and result in hexadecimal.
4. Observe the operands, result, and sign (if negative) on the 7-segment displays.

## Repository Structure
```
5bit-binary-subtractor/
├── README.md          # Project documentation
├── PROJECT.circ    # Logisim circuit file
```

## Future Enhancements
- Add support for signed binary inputs.
- Extend the circuit to handle more bits.
- Implement a GUI for easier interaction.

## License
This project is open-source and available under the [MIT License](LICENSE).
