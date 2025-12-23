# iOS-Style Calculator for macOS

A beautiful, frameless calculator app inspired by iOS, built with Python and PyQt6.

<img src="https://help.apple.com/assets/68FABD5B6EF504342600E3E5/68FABD675A41CCC23909151C/en_US/fdfd728ae7af53da489f06a4dcb0b8c0.png" alt="Calculator App"/>

## Features
- **Design**: Clean, dark mode aesthetic with rounded corners and no window borders.
- **Animations**: Fluid button presses and display transitions.
- **Functionality**: Standard arithmetic, percentage, and chaining operations.

## Prerequisites
- **Python 3.9+**
- macOS (recommended for the best visual integration)

## Installation

1. **Open Terminal** and navigate to this folder:
   ```bash
   cd /path/to/Calculator
   ```

2. **Create a virtual environment** (recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## How to Run

1. Ensure your virtual environment is active (`source venv/bin/activate`).
2. Run the application:
   ```bash
   python3 src/main.py
   ```

## Controls
- **Mouse**: Click buttons to calculate. You can drag the window by clicking anywhere on the background.
- **Keyboard**:
  - `Esc`: Close the application (Exit).

## Troubleshooting
- **"Module not found" error**: Make sure you ran `source venv/bin/activate` before running the script.
- **Window frame appears**: The app is designed to be frameless. If your window manager overrides this, you might see a border.
