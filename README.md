# UART Implementation in Verilog 

During this project of Computer Structure and Microprocessors I implemented an Universal Asynchronous Receiver Transmitter (UART) module in Verilog. The UART handles serial communication, including data transmission and reception. Additionally, I created a test module to verify its functionality.

A UART is a peripheral device used for asynchronous serial communication. It allows data exchange between two devices.

![alt text](https://github.com/MohammadParsaTheFirst/UART_in_verilog/tree/main/images/uart.png)

## Functionality:
- UART sends data bits one by one, from the least significant to the most significant.
- Data is framed by start and stop bits, ensuring precise timing.

## Components:
- clock generator
- Shift Registers
- Read/Write 
- Serial Transmission

## Settings:
- Baude Rate
- Parity Bits



