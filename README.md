# Open Source Audit — Git

---

## 👤 Student Details

* **Name:** Niti Sinha
* **Registration Number:** 24MEI10011
* **Course:** Open Source Software (OSS NGMC)

---

## 💻 Chosen Software

* **Software Name:** Git
* **Category:** Version Control System
* **License:** GNU General Public License (GPL v2)

Git is a distributed version control system that helps developers track changes in their code and collaborate efficiently. It is widely used in both academic and industry environments. I chose Git for this project because I have already used it in basic form, but I wanted to understand how it works internally and why it is so important in open-source development.

---

## 📌 Project Description

This project focuses on analyzing an open-source software system from both technical and philosophical perspectives. Instead of just understanding what the software does, the aim is to explore why it was created, how it is used in real systems, and what values it represents.

In this audit, I studied Git’s origin, its licensing model, its role in the Linux ecosystem, and how it compares to proprietary alternatives. Along with the theoretical analysis, I also implemented practical tasks using Linux shell scripting to demonstrate hands-on understanding.

This project helped me connect theoretical concepts of open source with real-world usage.

---

## ⚙️ Requirements

To run this project properly, the following tools and environment are required:

* A Linux-based operating system (Ubuntu recommended)
* Bash shell (default in most Linux systems)
* Git installed on the system
* Basic knowledge of terminal commands

These requirements ensure that all scripts run smoothly and the outputs can be verified without errors.

---

## 🛠️ Setup Instructions

### 1. Install Git

Before running the scripts, Git must be installed on the system:

```bash
sudo apt update
sudo apt install git
```

This command installs Git using the system’s package manager.

---

### 2. Verify Installation

After installation, it is important to confirm that Git is working correctly:

```bash
git --version
```

This command displays the installed version of Git, ensuring that it is ready to use.

---

## 📂 Project Files

| File Name  | Description                                                  |
| ---------- | ------------------------------------------------------------ |
| script1.sh | Displays system information such as user, kernel, and uptime |
| script2.sh | Checks whether Git is installed and shows its details        |
| script3.sh | Analyzes system directories and their permissions            |
| script4.sh | Reads log files and counts occurrences of specific keywords  |
| script5.sh | Generates a personalized open-source manifesto               |

Each script is designed to demonstrate a specific concept from Linux and shell scripting.

---

## ▶️ How to Run Scripts

### Step 1: Give Execute Permission

Before running the scripts, permission must be granted:

```bash
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh
```

This step allows the system to treat the files as executable programs.

---

### Step 2: Execute Scripts

Run each script using the following commands:

```bash
./script1.sh
./script2.sh
./script3.sh
./script4.sh /var/log/syslog
./script5.sh
```

Each script performs a different task and displays output directly in the terminal.

---

## 📜 Detailed Script Explanation

### 🔹 Script 1 — System Identity Report

This script collects and displays basic system information such as the Linux distribution, kernel version, logged-in user, uptime, and current date. It helps in understanding how system-level information can be accessed using shell commands.

---

### 🔹 Script 2 — FOSS Package Inspector

This script checks whether Git is installed on the system. If it is installed, it displays details such as version and description. It also uses conditional statements to handle different cases, making it a good example of decision-making in shell scripting.

---

### 🔹 Script 3 — Disk and Permission Auditor

This script loops through important system directories and displays their size and permissions. It demonstrates how loops and command-line tools can be used together to analyze system resources.

---

### 🔹 Script 4 — Log File Analyzer

This script reads a log file line by line and counts how many times a specific keyword appears. It shows how file handling and condition checking can be done in shell scripts.

---

### 🔹 Script 5 — Open Source Manifesto Generator

This script interacts with the user by asking questions and generating a personalized text file based on the responses. It demonstrates user input handling and file creation.

---

## 🧠 Learning Outcomes

Through this project, I gained a better understanding of:

* The concept and importance of open-source software
* How Git works beyond basic usage
* The role of Linux in managing software systems
* Practical implementation of shell scripting concepts
* The connection between theory and real-world applications

This project helped me move from just using tools to actually understanding them.

---

## 📎 Notes

* All scripts were tested on a Linux system
* Outputs may vary slightly depending on system configuration
* Screenshots of execution are included in the project report

---

## 🚀 Conclusion

Overall, this project helped me understand Git not only as a tool but also as a part of a larger open-source ecosystem. It showed how collaboration and transparency play an important role in software development.

Working on both theoretical and practical aspects gave me a more complete understanding of open-source systems. In the future, I would like to explore contributing to open-source projects and improving my technical skills further.

---

