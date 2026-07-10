# 🏠 Smart Home Automation using OpenHAB

## 📌 Project Overview
This project demonstrates a Smart Home Automation system using OpenHAB running on Debian 12 in a VirtualBox virtual machine. The project integrates Java 21 (JDK 21), an OpenHAB automation platform, and a custom Java Agent for communication and monitoring.

## ✨ Features
- Smart Home Automation using OpenHAB
- Java 21 (JDK 21) environment
- Debian 12 Virtual Machine
- Custom Java Agent Integration
- MQTT Communication
- Automatic OpenHAB startup
- Automated Agent execution

## 🛠 Technologies Used
- Debian 12
- VirtualBox
- OpenJDK 21
- OpenHAB
- Java
- MQTT (Mosquitto)
- Git & GitHub

## 📂 Project Structure

```
Smart_Home/
├── agent_extract/
├── openhab-backup/
├── agent-0.0.1-SNAPSHOT.jar
├── openhab-agent.service
└── README.md
```

## ⚙ Installation

1. Install Debian 12 in VirtualBox.
2. Install OpenJDK 21.
3. Install OpenHAB.
4. Configure Mosquitto MQTT Broker.
5. Place the Java Agent JAR file.
6. Configure the OpenHAB service.
7. Start OpenHAB and the Agent.

## ▶ Running the Project

Start OpenHAB:

```bash
sudo systemctl start openhab
```

Check OpenHAB status:

```bash
sudo systemctl status openhab
```

Run the Agent:

```bash
java -jar agent-0.0.1-SNAPSHOT.jar
```

## 🎯 Applications

- Smart Home Automation
- IoT Monitoring
- Home Device Control
- MQTT-based Communication

## 👩‍💻 Developed By

**Karthigai Lakshmi**

BE Electronics and Communication Engineering (ECE)

Embedded Systems Intern – RGreen Technologies, Madurai

GitHub: https://github.com/Karthiga2611-ECE

---

⭐ If you like this project, don't forget to star the repository!
