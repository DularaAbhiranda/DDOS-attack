# 🛡️ CreedStorm - Cybersecurity Learning Repository

Welcome to **CreedStorm**, a beginner-friendly platform to explore the fundamentals of Distributed Denial-of-Service (DDoS) attacks in a controlled and educational setup. This repository introduces you to the **art of simulating and defending against cyber threats** in a secure environment.

> **⚠️ DISCLAIMER:** This repository is for educational and research purposes only. Any misuse of the code to harm, disrupt, or attack unauthorized systems is illegal and unethical. By using this repository, you agree to act responsibly and only test in controlled environments with proper authorization.

---

## 🎯 What is CreedStorm?

CreedStorm is a **cyber-themed DDoS simulation tool** designed to:
- Simulate DDoS-like behavior by opening multiple browser tabs to overload system resources.
- Provide an interactive **defense mechanism** to stop the simulation.
- Educate users about cybersecurity threats in a hands-on manner.

---

## 🌐 What is a DDoS Attack?

A **Distributed Denial-of-Service (DDoS) attack** is a type of cyberattack where multiple systems flood the bandwidth or resources of a targeted server, website, or network. The aim is to overwhelm the target, making it inaccessible to legitimate users.

### **How It Works:**
1. **Attack Initiation:** Multiple devices (often compromised by malware) generate a massive amount of traffic.
2. **Overloading Resources:** The target system’s bandwidth or computing resources are overwhelmed.
3. **Denial of Service:** Legitimate users cannot access the service, leading to disruptions.

### **Why Learn About DDoS?**
Understanding DDoS attacks is crucial for:
- Building secure systems.
- Learning mitigation strategies (e.g., rate limiting, firewalls).
- Strengthening your knowledge of cybersecurity fundamentals.

---

## 🚀 Features of CreedStorm

1. **DDoS Simulation**:
   - Simulates DDoS-like behavior by opening multiple browser tabs.
   - Helps understand system performance under stress.

2. **Interactive Defense Mechanism**:
   - After every minute, a popup window appears, allowing users to enter the defense code (`leavemealone`) to stop the simulation.
   - Displays a countdown timer in the popup.

3. **Automatic Browser Closure**:
   - On successful defense, all opened browser tabs/windows are automatically closed.

4. **Standalone Executable**:
   - Easily convert the Python script into a standalone application using PyInstaller.

---

## 📥 Getting Started

### Prerequisites

1. **Python 3.10+ Installed**:
   - Download Python from [python.org](https://www.python.org/).

2. **Install Required Libraries**:
   Run the following command to install dependencies:
   ```bash
   pip install psutil pillow
   ```

3. **Controlled Environment**:
   - Use a virtual machine or isolated network for testing.

---

### **Steps to Run CreedStorm**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/DularaAbhiranda/DDOS-attack.git
   cd DDOS-attack
   ```

2. **Activate the Virtual Environment (Optional)**:
   Create and activate a virtual environment for isolated testing:
   ```bash
   python -m venv .venv
   .\.venv\Scripts\activate  # On Windows
   source .venv/bin/activate   # On macOS/Linux
   ```

3. **Run the Program**:
   Execute the Python script to start the simulation:
   ```bash
   python script.py
   ```

4. **Observe Behavior**:
   - Browser tabs will start opening continuously.
   - After 1 minute, a popup window will appear asking for the defense code.

5. **Stop the Attack**:
   - Enter the defense code `leavemealone` in the popup window.
   - A success message, "You are safe now!" will appear.
   - All browser windows will close automatically.

6. **Incorrect Code**:
   - If you enter the wrong code, the popup will display "Try again," and the attack will resume.

---

## 🛠️ Building a Standalone Application

To convert the Python script into a standalone executable for easy sharing:

1. **Install PyInstaller**:
   ```bash
   pip install pyinstaller
   ```

2. **Package the Script**:
   ```bash
   python -m PyInstaller --onefile --noconsole --icon=app_icon.ico script.py
   ```

3. **Find the Executable**:
   The final executable will be in the `dist` folder:
   ```plaintext
   dist/script.exe
   ```

4. **Run the Executable**:
   Double-click the `script.exe` file to run the application.

---

## 🔐 Legal and Ethical Usage

- **Authorization**: Use these tools only on systems you own or have explicit permission to test.
- **Avoid Misuse**: Misusing this program to disrupt unauthorized systems is illegal.
- **Learning Purpose**: CreedStorm is designed for learning and improving cybersecurity awareness.

---

## 📄 License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 💡 Contribution Guidelines

We welcome contributions! Here’s how you can help:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Added feature-name"
   ```
4. Push your changes:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## 🎨 Cyber-Themed Highlights

- Explore **cybersecurity fundamentals** in a controlled setup.
- Learn about **DDoS attacks** and their impact.
- Understand how **defense mechanisms** work.
- Build your own **cyber-themed executable** to enhance learning!

---

### 🚨 Stay Safe, Stay Ethical! 🚨
