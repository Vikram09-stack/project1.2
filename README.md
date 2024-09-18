 XOR Gate Implementation in HDL

## Project Overview
This project demonstrates the implementation of an XOR gate using Hardware Description Language (HDL). The XOR gate is a fundamental digital logic gate that outputs true or 1 only when the two binary bit inputs to it are unequal.

## Files Included
- `Xor.hdl`: The HDL file containing the implementation of the XOR gate.
- `Xor.tst`: The test script to verify the functionality of the XOR gate.
- `Xor.cmp`: The comparison file to check the output against expected results.
- `Xor.out`: The output file generated after running the test script.

## HDL Implementation
The XOR gate is implemented using basic logic gates such as AND, OR, and NOT. The logic equation for the XOR gate is:
\[ \text{XOR}(A, B) = (A \text{ AND } \text{NOT}(B)) \text{ OR } (\text{NOT}(A) \text{ AND } B) \]

## How to Run
1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/yourusername/xor-hdl.git
    ```
2. Navigate to the project directory:
    ```sh
    cd xor-hdl
    ```
3. Run the test script to verify the implementation:
    ```sh
    HardwareSimulator Xor.tst
    ```

## Project Structure

xor-hdl/ ├── Xor.hdl ├── Xor.tst ├── Xor.cmp └── Xor.out


## Contributing
Contributions are welcome! Please fork this repository and submit pull requests.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Inspired by the Nand2Tetris course and the book "The Elements of Computing Systems" by Nisan and Schocken.

