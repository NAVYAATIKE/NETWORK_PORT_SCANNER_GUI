🔍 Network Port Scanner (Python GUI)
A fast and user-friendly Network Port Scanner built using Python and Tkinter.
This tool allows users to scan a range of ports on a target IP or hostname and identify open ports along with their services.

🚀 Features
✅ Scan ports for any IP address or hostname
✅ Custom port range selection (0–65535)
✅ Multi-threaded scanning for high speed
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
Queue (for thread communication)
📸 GUI Overview
Input:
Target (IP / Hostname)
Start Port
End Port
Buttons:
Start Scan
Stop Scan
Clear Results
Save Results
⚙️ How It Works
The user enters the target and port range.
The scanner resolves the hostname to an IP address.
Multiple threads scan ports simultaneously.
Open ports are identified using socket connections.
Results are displayed in real-time on the GUI.
▶️ How to Run
Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
📂 Output Example
[+] Port 80 (HTTP) is open
[+] Port 443 (HTTPS) is open
