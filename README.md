# 🚀 Selenium Grid Automation Framework

## 📌 Project Overview
This project demonstrates a distributed Selenium automation framework using Selenium Grid with Hub and multiple Nodes. It supports parallel test execution using TestNG across multiple machines (VMs).

---

## 🏗️ Architecture
- Selenium Grid Hub
- Multiple Node Machines (VMs)
- RemoteWebDriver for distributed execution
- TestNG for parallel execution

---

## ⚙️ Tech Stack
- Java
- Selenium WebDriver (4.x)
- Selenium Grid
- TestNG
- Maven
- Windows VM

---

## 🚀 Features
- Distributed test execution using Selenium Grid
- Parallel execution using TestNG
- RemoteWebDriver integration
- Multi-node browser execution
- Clean project structure using Maven
- Git-based version control

---

## ▶️ How to Run

### 1. Start Hub
```bash
java -jar selenium-server.jar hub

java -jar selenium-server.jar node --hub http://<hub-ip>:4444

Right click → Run as TestNG Suite
