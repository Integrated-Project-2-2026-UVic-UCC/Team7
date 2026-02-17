# 🤖 Autonomous Connect 4 Machine

University academic project focused on designing and developing a fully autonomous physical **Connect 4 (4 in a Row)** machine capable of playing against a human opponent.

The system will combine:

- Physical mechanical design  
- Raspberry Pi control system  
- Artificial Intelligence (Minimax + Alpha-Beta pruning)  
- Automatic piece recovery and mechanical sorting  
- Full autonomous game reset  

---

# 🎯 Project Objective

To build a fully autonomous machine capable of:

1. Detecting the board state  
2. Computing the optimal move  
3. Physically executing the move  
4. Recovering all pieces at the end of the match  
5. Mechanically sorting the pieces (without sensors)  
6. Automatically preparing for the next game  

The project is currently in the **early conceptual stage**.

---

# 🏗 System Architecture (Conceptual)

## Main Subsystems

### 1️⃣ Mechanical System
- Vertical 7x6 board  
- X-axis moving head mechanism  
- Piece drop system  
- Bottom trap door for board clearing  
- Fully mechanical piece sorting system (no sensors)  
- Vertical storage reservoirs  

### 2️⃣ Electronics
- Raspberry Pi (model TBD)  
- Stepper motor for lateral movement  
- Motor driver  
- Servo motor for piece release  
- Endstops for homing  
- Separate power supply for logic and motors  

### 3️⃣ Software
- AI engine  
- Game logic  
- Motion control  
- Detection system (camera or mechanical detection – TBD)

---

# 🧠 Artificial Intelligence

The AI uses:

- Minimax algorithm  
- Alpha-Beta pruning  
- Heuristic evaluation  
- Center-column prioritization  
- Immediate win/block detection  

The algorithm is optimized to run efficiently on a Raspberry Pi.

---

# 📁 Project Structure

