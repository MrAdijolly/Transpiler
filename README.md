# 🚀 Transpiler for a Custom Programming Language

This project implements a **transpiler (source-to-source compiler)** for a custom-designed programming language using **Flex** and **Bison**. It focuses on converting high-level language constructs into an intermediate representation while demonstrating core compiler design concepts.

---

## 📌 Features

- Lexical analysis with token generation  
- Syntax analysis using grammar rules  
- Abstract Syntax Tree (AST) construction  

### 🔹 Custom Control Structures
- `IF`, `ORIF`, `OR_ELSE`  
- `WHEN`, `DO-WHEN`, `FROM-TO`  
- `CHOICE-CASE`  

### 🔹 Built-in Function Handling
- I/O operations  
- Math functions  
- String manipulation  
- Memory utilities  

- Error detection and recovery  

---

## 🧰 Requirements

Make sure the following tools are installed:

- **Flex** (Lexical Analyzer Generator)  
- **Bison** (Parser Generator)  
- **GCC** (C Compiler)  

---

## ⚙️ Installation

### 🐧 Linux (Ubuntu/Debian)

```bash
sudo apt update
sudo apt install flex bison gcc
