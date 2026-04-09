# SmartCitySimulation
Smart City Simulation System is a Java-based project that models key city functions like population, energy, finance, and policies. It uses object-oriented design and custom exceptions to simulate real-world operations, ensuring modularity, error handling, and efficient management of urban systems.
# 🌆 Smart City Simulation v2.0

## 📌 Overview

Smart City Simulation is a Java-based system that models and analyzes the behavior of a modern city through interactive simulation.

The system integrates multiple urban subsystems such as transport, energy, water, finance, and population, allowing users to simulate daily operations, apply policies, and monitor city health in real time.

> 🤖 This project was developed as a **group project with AI-assisted implementation**, where system design, architecture, and feature direction were led by the team.

---

## 🚀 Key Features

* 📊 Interactive **Enhanced Dashboard**
* ⏱️ Run **day-by-day simulation**
* 🚨 Intelligent **System Alerts & Suggestions**
* 📄 Detailed **Simulation Reports**
* 📈 **Trends & Analytics (10-day tracking)**
* 🧾 **Event Logging System**
* 🎭 Multiple **Simulation Scenarios**
* ⚙️ Dynamic **Policy Management System**
* 💾 Save / Load / Backup city data

---

## 🧠 System Architecture

The project follows a modular **Object-Oriented Design**:

### 📦 Core Packages

```id="pkg1"
entities/     → Core data models (City)
systems/      → Simulation subsystems
managers/     → Controllers & logic managers
exceptions/   → Custom exception handling
```

### ⚙️ Main Systems

* Transport System 🚍
* Energy System ⚡
* Water System 💧
* Finance System 💰
* Population System 👥
* Happiness System 😊
* Simulation Engine 🔄

Each system interacts through **SystemDependencies**, creating realistic city behavior.

---

## 🎮 Menu Options

```id="menu2"
1. View Enhanced Dashboard  
2. Run One-Day Simulation  
3. View System Alerts  
4. View Detailed Report  
5. View Trends & Charts  
6. View Event Log  
7. Change Scenario  
8. Manage Policies (Update Settings)  
9. Save City Data  
10. View Saved Data  
11. Restore from Backup  
12. Exit  
```

---

## 🖥️ Sample Output

```id="output1"
SMART CITY DASHBOARD

City            : NovaTown (Day 1)
Population      : 25,000
Budget          : 12,348,545
Happiness       : 85/100
Status          : EXCELLENT

SYSTEMS:
Transport  → LOW traffic, 20 min travel
Energy     → 75% usage (STABLE)
Water      → 60% consumption
Finance    → Budget stable
```

---

## 🎭 Simulation Scenarios

* Normal Day
* Festival Day 🎉
* Power Crisis ⚠️
* Transport Strike 🚫

Each scenario dynamically impacts multiple systems.

---

## ⚙️ Policy Management

Users can modify city policies in real-time:

* Transport (add buses)
* Energy (increase production)
* Finance (adjust taxes)
* Water (increase supply)

Policies directly affect simulation outcomes.

---

## 💾 Data Persistence

* Save current city state
* Load previous simulation data
* Restore from backup

---

## 🛠️ Technologies Used

* Java
* Object-Oriented Programming (OOP)
* File Handling
* Console-based UI

---

## 👥 Team Contribution

| Member   | Responsibility                  | Contribution |
| -------- | ------------------------------- | ------------ |
| Member 1 | Transport & Population Systems  | 33%          |
| Member 2 | Energy & Infrastructure Systems | 33%          |
| Member 3 | Finance & Simulation Control    | 34%          |

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone <your-repo-link>
```

2. Navigate to project folder:

```bash
cd smart-city
```

3. Run using script:

```bash
run.bat
```

OR run manually in IDE:

* Open in Eclipse / IntelliJ
* Run `SmartCitySimulation.java`

---

## 🧠 How It Works

* Each system simulates daily changes independently
* The **SimulationEngine** coordinates all systems
* **SystemDependencies** apply cross-system effects
* Example:

  * High energy usage → reduces happiness
  * High happiness → increases population

---

## ⚠️ Limitations

* Console-based (no GUI yet)
* Simplified real-world modeling
* No real-time external data integration

---

## 🔮 Future Improvements

* GUI Dashboard (JavaFX / Web)
* Real-time analytics & visualization
* AI-based prediction models
* Database integration (MySQL/PostgreSQL)

---

## 👤 Authors

Developed as a group project with AI assistance

* System design, architecture, and feature direction led by the team
* AI used as a development tool under human guidance

---

## 📜 License

This project is for educational and demonstration purposes.

---

## ⭐ Final Note

This project demonstrates:

* Strong OOP design
* System thinking & simulation modeling
* Multi-module architecture
* Real-world problem abstraction
