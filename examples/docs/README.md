## 📚 Documentation

The docs/ directory contains the technical documentation for the OpenFi Trade Engine.

This section is designed to provide a structured and detailed understanding of how the system works, how to integrate with it, and how to extend its functionality.

---

## 🧠 Purpose

The documentation is intended for:

- Developers integrating OpenFi into their trading workflows  
- Users configuring signal execution pipelines  
- Contributors extending the system architecture  

---

## 📂 Structure

Each file inside this directory focuses on a specific component of the system:

- architecture.md  
  Overview of the system design and core components  

- signal-flow.md  
  End-to-end flow from TradingView signals to execution  

- alert-format.md  
  Standardized JSON structure for alerts  

- setup.md  
  Step-by-step guide to connect TradingView and execution environments  

- integrations.md  
  Details about supported connectors (MT4, MT5, PineConnector)  

---

## ⚙️ How to Use

Start with architecture.md to understand the system design,  
then follow setup.md to configure your environment.

For implementation details, refer to:
- Signal processing → signal-flow.md  
- Alert structure → alert-format.md  
- Execution layer → integrations.md  

---

## 🔄 Updates

This documentation is actively maintained and will evolve alongside the system as new modules and integrations are introduced.

---

## 🧩 Related

For practical usage examples, refer to the examples/ directory.  
For a high-level overview, see the main `README.md
