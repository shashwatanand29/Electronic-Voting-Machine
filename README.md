# 🗳️ Electronic Voting Machine using ATmega32

This is a simulated **Electronic Voting Machine (EVM)** built using the **ATmega32 microcontroller**, designed and tested in **Proteus**. The project allows users to cast votes via a **4x4 matrix keypad**, with real-time updates and results displayed on a **20x4 LCD**. Firmware is written in **C** using **Microchip Studio (formerly Atmel Studio)**, and the `.hex` file is used for simulation in Proteus.

---

## 🚀 Features

- ✅ ATmega32-based voting system
- 🔢 4x4 Matrix Keypad for voter input
- 🖥️ 20x4 LCD to display voting options and results
- 💾 Vote count logic with real-time display
- ⚙️ Fully functional simulation in Proteus

---

## 🧠 Workflow

1. **System Initialization**  
   Upon powering up, the LCD displays a welcome message and instructions for the voter.

2. **Casting a Vote**  
   - The voter is prompted to press a key corresponding to a candidate number.
   - The system reads the key input via the 4x4 matrix keypad.
   - A confirmation message is displayed after a successful vote is cast.

3. **Vote Counting**  
   - Each vote is counted and stored in an array using internal memory of ATmega32.
   - The system ensures only valid key entries are accepted.

4. **Results Display**  
   - When a specific key (e.g., `*` or `#`) is pressed (by an authorized person), the total vote counts for all candidates are displayed on the LCD.
   - The LCD automatically scrolls through results if needed due to limited display space.

---

## 🛠️ Tools & Technologies

| Tool               | Purpose                           |
|--------------------|-----------------------------------|
| ATmega32           | Main microcontroller              |
| Microchip Studio   | Firmware development (C Language) |
| Proteus Design Suite | Circuit simulation & schematic   |
| 4x4 Matrix Keypad  | Voter input                       |
| 20x4 LCD Display   | Display interface                 |

---
