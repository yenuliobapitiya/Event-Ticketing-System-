# 🎟️ Real-Time Event Ticketing System (Backend)


## 📌 Project Overview

- **Goal**: To simulate a dynamic ticketing environment handling concurrent ticket releases and purchases while maintaining data integrity.
- **Pattern Used**: Producer-Consumer
- **Concurrency**: Handled using Java multi-threading and synchronization
- **Focus Areas**:
  - Multi-threading with Runnable interface
  - Thread-safe data structures
  - Logging and error handling
  - Configuration management

---

## 🛠️ Features

- 👨‍💼 Multiple vendors (producers) releasing tickets concurrently
- 🧑‍💻 Multiple customers (consumers) purchasing tickets simultaneously
- 📦 Thread-safe shared ticket pool
- ⚙️ Configurable system parameters (total tickets, release/retrieval rate, max capacity)
- 🧾 Console and file logging for system activities
- 🚨 Exception handling with meaningful messages

---
