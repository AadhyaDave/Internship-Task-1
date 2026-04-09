# 🔬 VLSI Internship – Task 1
### Introduction to VLSI Design Flow & Basic Digital Logic Implementation
**Organisation:** Maincrafts Technology  |  **Intern:** Aadhya
**College:** GH Patel College of Engineering & Technology  |  **Branch:** ECE (2023–27)

---

## 📌 Objective
Build a strong foundation in VLSI fundamentals by understanding:
- What VLSI is and where it is used in the industry
- How a VLSI chip is designed from idea to fabrication (9-step design flow)
- Basic digital logic concepts that form the core of all VLSI systems

---

## 📁 Deliverables

| File | Description |
|------|-------------|
| `Task1_VLSI_Report_Aadhya.pdf` | Formal report — design flow, truth tables, circuit analysis, observations |
| `Task1_VLSI_Simulator_Aadhya.html` | Interactive browser-based logic gate & Half Adder simulator |

---

## 🧠 Concepts Covered

### Part A — What is VLSI?
- Definition and IC integration levels (SSI → ULSI)
- Real-world applications: smartphones, AI accelerators, medical devices, automotive ECUs

### Part B — VLSI Design Flow (9 Steps)
```
System Specification → Architecture Design → RTL Design → Functional Verification
→ Synthesis → Physical Design → Timing & Power Analysis → Fabrication → Testing
```
> Task 1 focuses on steps 1 (System Specification) and 2 (Architecture Design).

### Part C — Digital Logic Fundamentals
- Binary logic levels, Boolean algebra (10 laws including De Morgan's theorem)
- Logic simplification techniques

### Part D — Logic Gates Simulated

| Gate | Expression | Key Property |
|------|-----------|--------------|
| AND  | A · B     | Output HIGH only when all inputs HIGH |
| OR   | A + B     | Output HIGH when any input HIGH |
| NOT  | A'        | Inverts input — core CMOS building block |
| NAND | (A · B)'  | Universal gate |
| NOR  | (A + B)'  | Universal gate |
| XOR  | A ⊕ B     | HIGH when inputs differ — used in adders |

### Part E — Half Adder Circuit
Combinational circuit implementing 1-bit binary addition:
```
Sum   = A XOR B   (A ⊕ B)
Carry = A AND B   (A · B)
```

| A | B | Sum | Carry |
|---|---|-----|-------|
| 0 | 0 |  0  |   0   |
| 0 | 1 |  1  |   0   |
| 1 | 0 |  1  |   0   |
| 1 | 1 |  0  |   1   |

---

## 🛠️ Tools Used
- **Logisim** — offline digital logic circuit simulator
- **CircuitVerse** — online interactive circuit design
- **ReportLab (Python)** — PDF report generation
- **HTML / CSS / JavaScript** — interactive simulator

---

## ✅ Key Learnings
- Verified all 6 logic gates against truth tables through simulation
- Confirmed NAND and NOR as universal gates
- Designed and tested a Half Adder circuit for all 4 input combinations
- Understood the end-to-end VLSI design flow used in the semiconductor industry
- Applied Boolean algebra laws (De Morgan, absorption, complement) in circuit analysis

---

## 📚 References
- Tutorialspoint VLSI Design: https://www.tutorialspoint.com/vlsi_design/index.htm
- Digital Logic Basics (GeeksforGeeks): https://www.geeksforgeeks.org/digital-electronics-digital-logic/
- Digital Design — M. Morris Mano (Reference textbook)
- Logisim Official: http://www.cburch.com/logisim/

---

*Part of the Maincrafts Technology VLSI Internship structured task series.*
