🔍 Network Port Scanner (Python GUI)

A fast and user-friendly Network Port Scanner built using Python and Tkinter.
This tool allows users to scan a range of ports on a target IP or hostname and identify open ports along with their associated services.

🚀 Features
✅ Scan ports for any IP address or hostname
✅ Custom port range selection (0–65535)
✅ Multi-threaded scanning for high performance
✅ Real-time progress tracking
✅ Displays open ports with service names
✅ Simple and clean GUI (Tkinter)
✅ Save scan results to a file
✅ Stop scan anytime
🛠️ Technologies Used
Python 3
Socket Programming
Threading (Multithreading)
Tkinter (GUI)
Queue (Thread Communication)
📸 GUI Overview
🔹 Inputs
Target (IP / Hostname)
Start Port
End Port
🔹 Controls
▶️ Start Scan
⛔ Stop Scan
🧹 Clear Results
💾 Save Results
⚙️ How It Works
The user enters the target IP/hostname and port range.
The scanner resolves the hostname into an IP address.
Multiple threads are created to scan ports simultaneously.
Each thread attempts to establish a socket connection.
Open ports are identified and displayed in real-time.
▶️ How to Run
1. Clone the Repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
2. Run the Application
python main.py
📂 Output Example
[+] Port 80 (HTTP) is open
[+] Port 443 (HTTPS) is open
⚠️ Disclaimer

This tool is intended for educational purposes only.
Do not use it to scan networks or systems without proper authorization.

💡 Future Improvements
🔐 Service version detection
🌐 OS fingerprinting
📊 Export results in multiple formats (CSV, JSON)
🧠 Integration with vulnerability scanners
