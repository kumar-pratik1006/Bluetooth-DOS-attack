# Bluetooth-DOS-attack
This program will never allow any bluetooth device to connect by performing DOS attack on it. 💻

# 🔥 Bluetooth DoS Attack Script (For Educational Use Only)

This project demonstrates a basic **Denial-of-Service (DoS)** attack targeting Bluetooth-enabled devices using Python and system tools. It is intended **strictly for educational and ethical hacking purposes** — to learn about vulnerabilities and how to prevent them.

> ❗ **Disclaimer:** This repository is meant for cybersecurity learning and ethical testing on devices you own or have permission to test. Do not use this script to attack others' devices without consent — doing so is illegal and unethical.

---

## 🧠 What is a Bluetooth DoS Attack?

A **Bluetooth Denial of Service attack** overwhelms a Bluetooth device with connection requests or malformed packets, making it unresponsive or disconnecting it from other devices.

This script uses command-line Bluetooth tools (`l2ping`, etc.) to simulate a DoS by flooding a target device with pings.

---

## 🚀 Features

- Easy-to-use command-line tool.
- Floods target device with continuous `l2ping` packets.
- Can be stopped anytime manually.
- Minimal setup needed.

---

## 🛠️ Requirements

- Linux OS (preferably Kali Linux or Ubuntu)
- Python 3.x
- `l2ping` tool (usually comes with `bluez` package)

### Install dependencies:
```bash
sudo apt update
sudo apt install bluez python3

⚙️ Usage

1. Clone the repository:

git clone https://github.com/kumar-pratik1006/Bluetooth-DOS-attack.git
cd Bluetooth-DOS-attack


2. Run the Python script:

sudo python3 bluetooth_dos.py


3. Enter the target device’s Bluetooth MAC address when prompted.



> ⚠️ Run with sudo for Bluetooth tools to work correctly.




---

🧪 Example MAC Address

Target MAC: AA:BB:CC:DD:EE:FF

Make sure the target device is discoverable.


---

🔐 Legal Notice

This tool is intended for penetration testing and security research. The author is not responsible for any misuse or damage caused by this tool. Always ensure you have explicit permission before testing any network or device.


---

👨‍💻 Author

Kumar Pratik

GitHub: @kumar-pratik1006

Project Type: Ethical Hacking / Security Tool



---

🌟 Star the Repo

If this project helped you learn something new or was useful, please consider ⭐ starring the repository!


---

📢 Contributing

Contributions and suggestions are welcome! Feel free to fork the repo and submit a PR.

---

Let me know if you want a Hindi version or want to add badges (like stars, forks, license).

