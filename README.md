# PyBuster 🕵️‍♂️🔍

A fast, multi-threaded, GUI-based directory and file busting tool built with Python. PyBuster is designed to help security researchers, penetration testers, and developers discover hidden paths, endpoints, and assets on web servers.

## ✨ Features

* **Modern GUI**: Built with Tkinter and styled with `ttkthemes` (`arc` theme) for a clean, intuitive interface.
* **Multi-Threaded Performance**: Configurable concurrent worker threads (up to 500) powered by thread pools and queues for high-speed scanning.
* **Granular Status Code Filtering**: Instantly toggle visibility for specific HTTP response status classes (2xx, 3xx, 4xx, 5xx, or all).
* **Stealth & User-Agent Rotation**: Automatically rotates requests across a pool of modern browser User-Agents.
* **Export Capabilities**: Export discovered paths directly into formatted `.txt` or `.csv` files for reporting and audit logs.
* **Quick Clipboard Integration**: Double-click any discovered URL to copy it directly to your clipboard.
* **Real-Time Telemetry**: Real-time progress bar, request counters, elapsed time, and thread health indicators.

## 🛠️ Prerequisites

* Python 3.10+
* Dependencies:
  ```bash
  pip install -r requirements.txt
  ```

## 🚀 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AryaMehr-Nam/Sample-DirBuster.git
   cd Sample-DirBuster
   ```

2. **Install requirements:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the tool:**
   ```bash
   python DirBuster.py
   ```

4. **Provide input:**
   - Enter your target URL (e.g. `http://example.com`)
   - Select your wordlist file (`.txt`)
   - Adjust concurrent threads (default: 30)
   - Click **Start Scan**

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
