### KeyLogger

## Description

This project is an educational implementation of a keylogger using Python. A keylogger is a program that records keystrokes on a computer. This software is intended solely for educational purposes, to understand how keyloggers work and to help develop better security measures against such threats.

## Functionality

- **Keystroke Logging**: Records all keystrokes made by the user.
- **File Logging**: Stores the recorded keystrokes in both text and JSON formats.
- **GUI Control**: Start and stop the keylogger using a simple graphical user interface.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/VamsiKrishna308/KeyLogger.git
    ```

2. Install the required dependencies:
    ```sh
    pip install pynput
    ```

## Usage

1. **Run the keylogger**:
    ```sh
    python keylogger.py
    ```

2. **Start the keylogger**:
    - Open the GUI and click the "Start" button to begin keylogging.
    - The keystrokes will be saved in `key_log.txt` and `key_log.json` files.

3. **Stop the keylogger**:
    - Open the GUI and click the "Stop" button to stop keylogging.

## Files

- `keylogger.py`: The main script to run the keylogger.
- `key_log.txt`: Text file where the keystrokes are logged.
- `key_log.json`: JSON file where the keystrokes are logged.
- `requirements.txt`: List of dependencies required to run the keylogger.

## Dependencies

- `tkinter`: For the graphical user interface.
- `pynput`: For capturing keyboard events.
