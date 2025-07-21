# IrisSpring Cybersecurity Assistant

[![Buy on Gumroad](https://img.shields.io/badge/Gumroad-Buy%20Now-blueviolet?logo=gumroad&style=for-the-badge)](https://gumroad.com/l/irisspring)


IrisSpring Cybersecurity Assistant is a sleek, blue-themed Flask web app that scans a company’s network and system security posture, provides detailed reports, and can optionally apply automatic fixes for common cybersecurity issues.

---

## Features

- 🔍 Scan system firewall status, antivirus installation, and pending updates  
- 📊 Generate a clear and detailed scan report  
- 🛠️ Apply automatic fixes like enabling firewall, installing antivirus, and applying updates  
- 💻 Responsive, clean blue-themed web interface with interactive scan and fix buttons  
- ⚙️ Modular backend with separate tools for each scan/fix task  
- 🗂️ Save scan reports for historical reference  

---

## Installation

1. Clone this repo:

   ```bash
   git clone https://github.com/JRPagan23/irisspring-wifi-guard.git
   cd irisspring-wifi-guard

Create a Python virtual environment and activate it:
python3 -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows

Install dependencies:
pip install -r requirements.txt

Run the app:
python app.py

Open your browser and go to: http://127.0.0.1:5000

Usage

Click Start Scan to perform a security scan of the system.

Click Fix Now to automatically fix detected issues.

View scan reports and fix results through the web interface.

Project Structure:
irisspring_assistant/
├── public/                      # Static files (CSS, JS)
├── templates/                   # HTML templates
├── tools/                       # Backend scan and fix modules
├── utils/                       # Utility modules
├── reports/                     # Saved scan reports (JSON)
├── app.py                      # Flask app entry point
├── scanner.py                  # Scanning engine
├── fixer.py                    # Automatic fix engine
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation

Next Steps

Extend scanning tools for more checks (Wi-Fi security, software vulnerabilities, etc.)
Add user authentication and role-based access control
Integrate with real-time notifications and alerts
Package as a desktop or mobile app

Contact

Developed by Jorge Rodriguez Pagan
GitHub: JRPagan23


License

This project is licensed under the MIT License.
