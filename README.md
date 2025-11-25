# Python Learning Practice

This repository contains my personal practice code while learning the fundamentals of Python programming.

I created this repo to track my learning journey and improve my coding skills day by day.

## 📚 Topics Covered

## Day 1
- Hello World
- Print Statement
- Print number
- Python Indention 

## Day 2
- variables
- datatypes
- input-output ( mini assigemnet enter user name, age and city)

## Day 3
- 
- 
- 



## 🎯 Purpose of This Repository

- To document my Python learning progress  
- To practice coding consistently  
- To build a GitHub portfolio for future opportunities  
- To learn Git & GitHub workflow (commit, push, version control)

## 🚀 How to Run the Code

📘 Python Setup & Running Guide

This guide explains how to install Python, check versions, run Python code using the terminal, and execute programs using VS Code.

✅ 1. Check Python Version

Open your terminal or command prompt and run:

Windows
python --version
py --version

macOS / Linux
python3 --version
python --version


If you see something like Python 3.11.x, Python is installed.

✅ 2. Install Python (Official Download)

Download from the official site:

👉 https://www.python.org/downloads/

Windows Install Steps

Run the installer.

Make sure to check:
✔ Add Python 3.x to PATH

Click Install Now.

Verify installation:

python --version
py --version

macOS

Install using:

Python.org installer
OR

Homebrew:

brew install python


Check version:

python3 --version

Linux (Ubuntu/Debian)
sudo apt update
sudo apt install python3 python3-venv python3-pip
python3 --version

✅ 3. Which Command Should You Use?

Windows:
py or python

macOS & Linux:
python3 (recommended)

Use whichever command returns a Python 3.x version.

✅ 4. Create Your First Python File

Create a folder (example: python-practice)

Inside it create a file named:

example.py


Add code:

print("Hello, Mukul!")

✅ 5. Run Python File in Terminal
Windows
python example.py


or

py example.py

Windows (specific version)
py -3.11 example.py

macOS / Linux
python3 example.py

✅ 6. Run Python Code in VS Code
A) Install Required Software

Install VS Code

Install the Python extension (by Microsoft)

B) Open Your Project
File → Open Folder → Select your folder

C) Select Python Interpreter

Press Ctrl + Shift + P

Type:

Python: Select Interpreter


Choose the Python 3.x version

D) Run Python File in VS Code
Method 1: Play Button

Open the file → Click Run ▶ (Run Python File)

Method 2: Keyboard Shortcut

Ctrl + F5 → Run without debugging

F5 → Run with debugging

Method 3: Terminal

Open terminal in VS Code:

Ctrl + ~


Run:

python example.py
py example.py
python3 example.py

✅ 7. (Optional) Create a Virtual Environment
Create venv:
python -m venv venv
# or
python3 -m venv venv

Activate venv:
Windows CMD:
venv\Scripts\activate

Windows PowerShell:
.\venv\Scripts\Activate.ps1

macOS/Linux:
source venv/bin/activate


After activation → select this interpreter in VS Code.

✅ 8. Common Problems & Fixes
❌ python: command not found

→ You didn’t check “Add to PATH” during install
Fix: reinstall Python or use py (Windows)

❌ VS Code: No interpreter selected

→ Press Ctrl + Shift + P → select interpreter

❌ File not running

→ Ensure file ends with .py (not .txt)

❌ Python 2.x running

→ Use python3 or select correct interpreter

🎉 You Are Ready!

This README gives you everything needed to install Python, write code, and run programs from both terminal and VS Code.

