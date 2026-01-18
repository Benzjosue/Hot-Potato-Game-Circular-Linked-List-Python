# Counting-Out Game (Josephus Simulation) — Python / Tkinter

A Python-based implementation of the classic **Josephus Problem**, combining core data structures with an interactive graphical user interface. This project demonstrates circular linked list design, pointer-based traversal, and dynamic GUI updates using Tkinter.

---

## 🔧 Technical Highlights
- Implemented a **custom Circular Linked List** to model player rotation.
- Applied **pointer-based traversal and node removal** to eliminate every *k-th* player while preserving circular structure.
- Built an **interactive Tkinter GUI** to visualize gameplay and dynamically update player states.
- Simulated the Josephus elimination process across configurable player counts.

---

## 🛠 Built With
- **Language:** Python 3
- **GUI Framework:** Tkinter
- **Development Tools:** Git, GitHub, Visual Studio Code

---

## ⚙️ How It Works
1. Players are added as nodes in a circular linked list.
2. The algorithm iterates *k* steps through the list to identify the next elimination target.
3. The selected node is removed using pointer reassignment.
4. The GUI updates in real time to reflect remaining players until a winner remains.

---

## ▶️ Installation & Usage
```bash
git clone https://github.com/benzjosue/counting-out-game.git
cd counting-out-game
python josue_benz_hw_5.py
