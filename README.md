# 🧩 Sudoko Solver & Generator

A Python-based Sudoku tool that can **solve** and **generate** puzzles on the command line.

[![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)]()

---

## 🔍 Overview

A command-line application to:
- Automatically **solve** 9×9 Sudoku puzzles from text files (using backtracking & heuristics).
- **Generate** new puzzles with adjustable difficulty levels.
- **Validate** puzzles to confirm legality and solvability.

---

## 🚀 Features

- ✅ **Backtracking solver** with optional heuristics.
- 🔄 **Puzzle generator** with difficulty settings.
- 📥 **Validation tool** to check input puzzle correctness.
- ⚙️ Easy-to-read console output for solved/unsolved puzzles.

---

## 📦 Installation

```bash
git clone https://github.com/YourUsername/Sudoko.git
cd Sudoko

python3 -m venv venv
source venv/bin/activate      # on Linux/macOS
venv\Scripts\activate.bat     # on Windows

pip install -r requirements.txt
