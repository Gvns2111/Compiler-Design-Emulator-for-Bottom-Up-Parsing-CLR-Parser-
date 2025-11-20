# Emulator for Bottom-Up Parsing – CLR (LR(1) Parser)

## 📌 Overview
This project implements a **Canonical LR(1) parser (CLR Parser)** capable of 
correctly parsing LR(1) grammars using a bottom-up parsing strategy.

It constructs:
- LR(1) Item Sets  
- ACTION & GOTO tables  
- Shift/Reduce operations  
- Accept/Reject output  

The system also visually represents each parsing phase.

## 🚀 Features
- Full LR(1) grammar support  
- LR(1) item generation  
- Closure and GOTO calculations  
- Parsing table construction  
- Web interface for grammar + input string testing  

## 📂 Project Structure
- `items.php` – LR(1) item generation logic
- `parse.php` – Parsing engine
- `grammar/` – Predefined grammar files
- `tables/` – ACTION & GOTO tables

## 📘 Algorithms Used
- **CLOSURE(I)**  
- **GOTO(I, X)**  
- Canonical LR(1) Table Construction  
(Algorithms referenced from project document – page 5–7 :contentReference[oaicite:1]{index=1})

## 🧪 Sample Output
- Shows Item sets
- ACTION/GOTO table
- Step-by-step shift-reduce parsing

## 📄 Report
Report is included as `CD PROJECT FINAL.pdf`.
