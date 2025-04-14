# 🐍 Snake Game on FPGA — *Pixel-Python*

A hardware-level implementation of the classic Snake Game, designed and developed on **FPGA** using **C** and **VGA output**.  
This project demonstrates digital game design principles combined with embedded programming for real-time hardware rendering.

---

## ⚡ Project Overview

This Snake Game is built for FPGA boards and displayed on a VGA-compatible monitor.  
It uses a combination of:

- **C language logic** for game mechanics.
- FPGA hardware for execution and display.
- VGA signaling to render the game visuals.

---

## 🎮 Features

- Snake can move left-right or up-down and have to get food within certain number of moves.
- Score tracking via simple counters.
- Smooth real-time rendering on VGA display.
- Minimal hardware resource utilization.

---

## 💻 Technologies & Tools

- **FPGA Board:** [Your FPGA board name, e.g., Xilinx Basys 3, Intel DE10-Lite]
- **Programming Language:** C  
- **Display Output:** VGA (640x480 resolution)  
- **Development Environment:** [e.g., Vivado, Quartus Prime, ModelSim]  
- **Simulation Tools:** [e.g., ModelSim, ISim]

---

## 🚀 How to Run

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/IIUday/Pixel-Python.git
   
   ```

2. **Open the project** in your preferred FPGA development suite (Vivado, Quartus, etc.).

3. **Synthesize** the hardware design.

4. **Program the FPGA board** using the generated bitstream.

5. **Connect a VGA monitor** to the FPGA board.

6. Power on the setup and start playing using:
   - Push-buttons / switches on the FPGA for direction control.
   - Snake will be displayed in real-time on the VGA monitor.

---
## 📂 Project Structure

```
Pixel-Python/
├── game.c
├── Readme.md

```

---

## 💡 Key Learning Outcomes

- Understanding VGA signal timing and pixel clock generation.
- Embedded game logic implementation using hardware constraints.
- Real-time interaction with hardware using input peripherals.
- Optimization of hardware resource usage.

---

## 🏆 Future Enhancements

- Add sound effects using audio output peripherals.
- Difficulty modes with increased snake speed.
- Save and display high scores using onboard memory or external EEPROM.
- Multiplayer support with additional input buttons.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
