# 🚀 Selenium Grid Automation Framework

## 📌 Project Overview
This project demonstrates a distributed Selenium automation framework using Selenium Grid with Hub and multiple Nodes. It supports parallel test execution using TestNG across multiple machines (VMs).

---

## 🧪 Project Demo
- Parallel execution across multiple VMs using Selenium Grid  
- Distributed browser execution using RemoteWebDriver  

---

## 🔄 Execution Flow
Test → Hub → Node → Browser Execution  

---

## 🏗️ Architecture
- Selenium Grid Hub  
- Multiple Node Machines (VMs)  
- RemoteWebDriver for distributed execution  
- TestNG for parallel execution  

---

## 📁 Project Structure

src/
├── test/java
├── test/resources
├── pom.xml
└── testng.xml


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

### 1. Start Selenium Hub

java -jar selenium-server.jar hub

2. Start Node(s)

java -jar selenium-server.jar node --hub http://<hub-ip>:4444

3. Run Tests (TestNG)

Right click → Run as TestNG Suite

📊 Key Achievements
Implemented Selenium Grid with Hub and multiple Nodes
Enabled parallel execution using TestNG
Executed tests across multiple virtual machines
Improved execution efficiency using distributed testing
