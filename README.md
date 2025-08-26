# CodeAlpha_BasicNetworkSniffer

---

# 🐍 Basic Network Sniffer

A simple yet powerful packet sniffer with a friendly graphical interface built using **Tkinter** and **Scapy**.
This tool allows you to monitor live **IPv4 traffic**, view **source/destination IP addresses**, and see **real-time protocol statistics** — all within a streamlined GUI.

---

## 🚀 Features

* 🔄 Real-time IP packet sniffing powered by **Scapy**
* 🎛️ Interactive GUI built with **Tkinter**
* 🌐 Displays source/destination IPs and protocols (**TCP, UDP, ICMP, Others**)
* 📊 Live statistics: packet counts per protocol and total captured
* 🟢 **Start** and 🔴 **Stop** sniffing with buttons
* 🧾 Summary report shown after stopping the capture

---

## 🖼️ Screenshot

*(Add your screenshot below — e.g., rename it to `screenshot.png` and place it in your repo)*

![Packet Sniffer GUI](screenshot.png)

---

## 📦 Requirements

* Python 3.x
* Scapy → `pip install scapy`
* Tkinter (comes pre-installed with most Python distributions)

---

## 🔧 Installation

```bash
git clone https://github.com/yourusername/packet-sniffer-tk.git
cd packet-sniffer-tk
pip install scapy
```

---

## ▶️ Usage

Run the sniffer with:

```bash
python sniffer.py
```

➡️ A Tkinter window will appear where you can **Start** and **Stop** packet sniffing.

⚠️ **Note:** On some systems you may need to run with admin/root privileges to capture packets:

```bash
sudo python sniffer.py
```

---

## 🛠️ Troubleshooting

* **Permission Denied** → Run as Administrator (Windows) or with `sudo` (Linux/macOS).
* **No packets captured** → Ensure you are connected to a network and not blocking traffic with a firewall.
* **Tkinter not found** → Install Tkinter manually (`sudo apt-get install python3-tk` on Ubuntu).

---

## 📌 Roadmap / Future Improvements

* Save captured packets to `.pcap` format
* Add filtering by protocol or IP address
* Dark mode UI
* Cross-platform testing (Windows/Linux/macOS)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to add.

---

## 📜 License

[MIT License](LICENSE)

