# Electronic-Voting-Machine-Using-STM32

### Overview
This project demonstrates the design and implementation of a **secure Electronic Voting Machine (EVM)** using the **STM32 microcontroller**. Built as part of the Microcontrollers Laboratory course, the system allows voters to cast votes via push buttons, ensures single-vote integrity with a software lock, and displays real-time results on an LCD.

### Key Highlights
- **Microcontroller**: STM32 (programmed using STM32CubeIDE)
- **Input**: 4 Push buttons (one per candidate)
- **Output**: 16x2 LCD display for vote counts and winner
- **Security Feature**: Software-based lock mechanism to prevent multiple votes per session
- **Modes**: Supports both manual and simulated (random) voting
- **Real-time Results**: Displays candidate-wise votes and final winner

### Objectives
- Implement a reliable and tamper-proof voting system using STM32
- Handle digital inputs, vote counting, and memory management
- Display live results and enforce one-vote-per-voter rule
- Gain hands-on experience in embedded C programming and hardware interfacing

### Results
- Successfully records and stores votes in internal memory
- Prevents multiple voting using software lock
- Accurately displays vote counts and declares winner on LCD
- Reliable performance in both manual and test voting scenarios

### Technologies & Components
- **STM32 Microcontroller**
- STM32CubeIDE + Embedded C
- 16x2 LCD Module
- Push Buttons, Breadboard, Jumper Wires
- GPIO, Debouncing, Memory Management

---

**Status**: Successfully implemented and demonstrated (October 2025)
