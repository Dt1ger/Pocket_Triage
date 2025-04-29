# Pocket_Triage
----------------------------
👨🏾‍💻 CyberD Pocket_Triage
----------------------------
CyberD Pocket_Triage is a lightweight Windows desktop tool designed to support rapid system triage and evidence gathering during cybersecurity investigations.

It offers a clean GUI to quickly scan, collect, and interact with a system — no command line needed unless you want it.

🖥️ Features
✅ Quick Anti-Virus Scan
Launches Microsoft's built-in MRT (Malicious Software Removal Tool) and displays the scan results.

✅ View Event Logs
Opens Windows Event Viewer with administrative privileges.

✅ Wi-Fi Profiles Viewer
Lists all saved Wi-Fi profiles stored on the local system.

✅ Remote Desktop Launcher
Quickly initiate a Remote Desktop (RDP) session to another machine.

✅ Open Terminal (Pocket Terminal)
An embedded terminal inside the app.

Execute multiple commands in sequence.

Outputs are logged live to the GUI.

Command session ends when you cancel.

✅ Download Outputs
Save all the displayed logs and terminal outputs into a .txt file.

✅ Clear Output
Instantly clear the output window.

✅ About CyberD Pocket_Triage
View instructions, feature list, and project information inside the app.

📥 Installation
Requirements

Python 3.9+
PyQt5 library
Windows OS (recommended for full functionality)

Install dependencies:
bash
Copy
Edit
pip install pyqt5
⚙️ Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/CyberD_Pocket_Triage.git
cd CyberD_Pocket_Triage
Run the app:

bash
Copy
Edit
python Pocket_v2.py
Optionally: compile into a .exe using PyInstaller.

bash
Copy
Edit
pyinstaller --onefile --windowed Pocket_v2.py

📖 How to Use the App
Launch the app.

Click any button:

Quick Anti-Virus Scan: starts MRT.exe scan.

View Event Logs: opens Event Viewer.

WiFi Profiles: displays stored WiFi profiles.

Remote: input an IP address to open Remote Desktop Connection.

Open Terminal: enter multiple Windows commands and view their output inside the app.

Download Outputs: save everything shown in the output window to a file.

Clear Output: resets the output window.

About CyberD_Pocket_Triage: shows the app's internal README and instructions.

✨ Screenshots

![image](https://github.com/user-attachments/assets/e2ee4cfd-c03c-4e1d-ae8a-1a121eb1124d)


🎨 Design Inspiration
The visual theme and design of CyberD Pocket_Triage are inspired by the vibrant colors and strong spirit of Jamaican culture and heritage.
Green, gold, and black elements reflect resilience, prosperity, and strength — values embedded in the purpose of this triage tool. 🇯🇲

👨‍💻 Author
Developed by Demar Powell
Version: 2.0








