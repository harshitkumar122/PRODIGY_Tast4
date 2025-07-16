# 🛡️ Task-04 – Simple Keylogger 

I developed a basic **Keylogger in Python** using the `pynput` module that logs every key pressed and stores it in a local file.  
This tool is intended strictly for **educational purposes** and demonstrates basic keyboard input tracking in Python

## 💡 Features

✔ Logs all keystrokes in real-time  
✔ Special keys are labeled (`[ENTER]`, `[TAB]`, `[SHIFT]`, etc.)  
✔ Keystrokes are saved to a file named `k.txt`  
✔ Pressing the `ESC` key automatically stops the logger  

## 📂 Output File Example (`k.txt`)

```text
hello world
[ENTER]
this is harshit jangid
[SPACE]Cybersecurity[SPACE]Intern
[BACKSPACE][BACKSPACE]
[SHIFT]H[SHIFT]I
[CTRL]
[ALT]
[Keylogger stopped]

🛠️ Tech Stack
✅ Python 3.x
✅ pynput library

⚙️ Installation
Install the required library:

bash
Copy
Edit
pip install pynput

▶️ How to Run
Save the following code in a file named keylogger.py
Open terminal and navigate to the script location
Run the script using:

bash
Copy
Edit
python keylogger.py
Start typing — everything will be saved to k.txt

Press ESC to stop the logger
