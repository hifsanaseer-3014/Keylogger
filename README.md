## **Keystroke Logger (Educational Simulation)**

## **Project Description**
A Python-based security tool designed to monitor and log keyboard input to a local text file for endpoint security analysis.

## **Execution Requirements**
* **Environment:** System Terminal / CMD (Required because IDE consoles often block hardware "hooks" and administrative permissions).
* **Permissions:** Administrative or Root privileges are required to access the keyboard event stream.

## **How to Run**

## **1. Install Dependencies**
```bash
pip install pynput
2. Execute with Sudo (Linux/Kali)
sudo python3 keylogger.py
## **3. Execute (Windows)**
Open CMD as Administrator and run:
python keylogger.py
Technical Breakdown
Listener
Uses pynput.keyboard.Listener to capture real-time events.

Logging
Data is saved to keyfile.txt using the 'a' (append) mode to preserve previous logs.

Persistence
The input() function keeps the main process active so the background listener can continue running.




