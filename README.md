# fpga-rf-packet-decoder
FPGA Verilog project to decode real-world 433 MHz RF packets in real time.

# FPGA-Based 433 MHz Wireless Packet Decoder

This project decodes 433.920 MHz RF signals from wireless remotes in real-time using Verilog on a Nexys A7 FPGA.  
The RF pulse train is captured by a receiver module and decoded by a finite state machine (FSM), then output over UART to a terminal.

## ⚙️ System Architecture


*Planned stretch goal: Add OLED display output using SSD1306 module via I2C.*

## 📁 Repo Structure

| Folder | Contents |
|--------|----------|
| `/src` | Verilog source files (FSM, UART, top-level) |
| `/doc` | Design notes, timing diagrams, protocol analysis |
| `/captures` | SDR# screenshots and signal captures |
| `/images` | Output photos from PuTTY or OLED display |
| `/testbench` | Verilog testbenches for simulation |
| `/xdc` | Vivado constraints for Nexys A7 board |

## 📷 Current Progress

- ✅ RTL-SDR capture tested and working
- 🛠️ Working on FSM pulse decoder
- 🖥️ UART output logic in progress
- ✅ GitHub repo structured

## 🎯 Goals

- Complete pulse width decoding FSM in Verilog
- Add UART output module for readable packet view
- Optionally display output on OLED (SSD1306)
- Write testbenches for pulse timing simulation

## 🧠 Why This Project?

This project demonstrates:
- FPGA Verilog skills
- Real-time signal processing
- Embedded systems design and debugging
- Hardware-to-software data pipelines (RF → UART)

## 📎 License

MIT
