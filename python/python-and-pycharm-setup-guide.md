# Python and PyCharm Setup Guide (macOS)

A step-by-step guide to install and configure Python and PyCharm Community Edition on macOS.  
This document explains both Homebrew and manual installation methods to prepare your environment for running Python code.

---

## Overview

This guide explains how to install Python and PyCharm Community Edition on macOS using either Homebrew or manual installation.  
It will help you prepare your environment to write and run Python code effectively.

---

## Step 1: Install Python on macOS

### Option A: Using Homebrew (recommended)

If you have Homebrew installed, open Terminal and run:

```
brew install python
```

Check that Python installed correctly:

```
python3 --version
```

You should see an output such as:

```
Python 3.x.x
```

---

### Option B: Manual download

If you do not use Homebrew:

1. Go to the official Python website: https://www.python.org/downloads/
2. Download the latest macOS installer (.pkg file)
3. Run the installer and follow the prompts
4. On the “Customize Installation” screen, make sure Add Python to PATH and Install Tcl/Tk are selected

Verify the installation:

```
python3 --version
pip3 --version
```

---

## Step 2: Install PyCharm Community Edition

### Using the command line

If you use Homebrew, run:

```
brew install --cask pycharm-ce
```

Or download it manually from JetBrains:  
https://www.jetbrains.com/pycharm/download/

---

## Step 3: Launch and configure PyCharm

1. Open PyCharm Community Edition from Applications or Spotlight (Cmd + Space → PyCharm)
2. On the Welcome Screen, choose Learn (or Projects if Learn is not visible)
3. Click Enable Access when prompted to allow plugin installation
4. Once setup completes, close and restart PyCharm

---

## Step 4: Verify setup

Inside PyCharm:

1. Create a new Python project  
2. Confirm that Python 3 is listed as the interpreter  
3. Open the built-in terminal and run:

```
python3 --version
```

If the correct version is displayed, your setup is complete.

---

## Troubleshooting

- If the Learn section is missing, go to  
  File → Learn and Teach → Browse Courses  
- If the interpreter is not found, go to  
  Preferences → Project → Python Interpreter → Add Interpreter  
  and select /usr/local/bin/python3

---

## Completion

You have now installed and configured Python and PyCharm on macOS.  
Your environment is ready to create and run Python programs.
