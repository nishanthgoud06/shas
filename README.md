# Smart Home Automation System (SHAS)

## Overview
SHAS is a Java-based project designed to simplify smart home automation. It provides developers with tools to control devices, schedule actions, group devices, log events, and monitor systems through an admin dashboard.

## 🔧 Core Features
1. **Turn devices on/off**: Control individual devices remotely.
2. **Schedule actions**: Automate tasks like turning on lights at specific times.
3. **Group devices into zones**: Organize devices into logical groups (e.g., Living Room, Bedroom).
4. **Log and replay device events**: Record device actions and replay them as needed.
5. **Admin dashboard**: Monitor and control all systems from a centralized interface.

## Design Patterns Used
The project leverages several design patterns to ensure scalability, maintainability, and flexibility:

| **Pattern**   | **Usage in Project**                                      |
|---------------|----------------------------------------------------------|
| **Singleton** | Central system controller for devices.                   |
| **Factory**   | Dynamically create devices based on type.                |
| **Strategy**  | Implement different control behaviors (manual, scheduled, remote). |
| **Command**   | Encapsulate actions like "turn on", "dim", "lock".       |
| **Observer**  | Notify system components (e.g., logs) when a device changes. |
| **Decorator** | Add logging or notification features to devices.         |
| **Builder**   | Create complex devices with optional configurations.     |
| **Adapter**   | Integrate external device APIs (e.g., smart bulb SDK).   |

## Getting Started

### Prerequisites
- **Java**: Ensure Java is installed on your system.
- **Maven**: Install Maven for dependency management.
- **IDE**: IntelliJ IDEA is recommended for development.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nishanthgoud06/shas.git