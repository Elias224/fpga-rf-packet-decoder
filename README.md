# fpga-rf-packet-decoder
FPGA Verilog project to decode real-world 433 MHz RF packets in real time.

# FPGA-Based 433 MHz Wireless Packet Decoder

This project decodes 433.920 MHz RF signals from wireless remotes in real-time using Verilog on a Nexys A7 FPGA.  
The RF pulse train is captured by a receiver module and decoded by a finite state machine (FSM), then output over UART to a terminal.

## ⚙️ System Architecture

