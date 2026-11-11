# 🌊 2050 Blue Pacific Strategy — Master Web Portal & Agentic AI Ecosystem

A comprehensive, interactive monitoring, public API integration, and multi-agent AI data engineering platform developed for the **Pacific Islands Forum Secretariat (PIFS)** and **United Nations Population Fund (UNFPA)** in support of the **Adviser – Data Analytics & Insights**.

This repository contains the complete codebase for the **2050 Master Web Portal**, unifying all regional Monitoring, Evaluation, and Learning (MEL) applications, public API connectors, and autonomous multi-agent AI pipelines for the **80 Core Outcome Indicators** under the *2050 Strategy for the Blue Pacific Continent*.

---

## 🚀 Key Applications & Portal Architecture

| File / Application | Description & Primary Function |
| :--- | :--- |
| **`2050_Master_Strategy_Portal_App.py`** | **Unified 5-Page Web Application** with password protection (`BluePacific2050`). Integrates the Executive Narrative, Practice Monitoring Portal, Live Public API Gateway, Agentic AI Control Tower, and Mind Map Knowledge Hub into a single interface. |
| **`2050_Agentic_Control_Tower_App.py`** | **Agentic AI Control Tower Dashboard.** Visualises real-time perception, planning, tool execution, self-correction logs, and Human-in-the-Loop review gates across the 4 autonomous AI agents. |
| **`2050_Agentic_Data_Pipeline_Engine.py`** | **Multi-Agent AI Execution Engine.** Autonomous backend engine featuring the *Supervisor Orchestrator*, *Ingestion Harvester*, *GESI Quality Auditor*, and *Narrative Synthesizer* agents. |
| **`2050_Live_Public_API_Demo_App.py`** | **Live Public API Demonstration Portal.** Connects directly to external CKAN, SDMX, and REST endpoints with latency tracking and dual-mode execution (Live Network vs. Air-Gapped Simulation). |
| **`pdh_live_api_connectors.py`** | **Production API Connector Library.** Resilient connector classes with automatic failover sequence for **SPC Pacific Data Hub**, **World Bank**, **WHO Observatory**, and **ADB Data Library**. |
| **`2050_Practice_Monitoring_System_App-v3.py`** | **Core Practice Monitoring Dashboard.** Relational database viewer, target vs. actual tracking, GESI/disability disaggregation audit, and 2027 Outcome Report intake. |
| **`run_all_apps.sh` / `run_all_apps.bat`** | **1-Click Terminal Launchers** (macOS/Linux bash & Windows batch) for launching any Streamlit application via an interactive menu. |

---

## 🔒 Security & Access Credentials

- **Default Master Portal Access Password:** `BluePacific2050`
- **Data Governance Standard:** Aligned strictly with **Pacific Statistics Methods Board (PSMB)** guidelines, ensuring national microdata remains with Member NSOs while aggregated outcome indicators feed the regional 2050 framework.

---

## 🛠️ Local Installation & Quickstart Guide

### 1. Prerequisites
- **Python:** Version 3.10, 3.11, or 3.12 installed on your machine.
- **Git:** (Optional) For cloning the codebase repository.

### 2. Install Required Packages
Open your terminal (macOS/Linux) or Command Prompt / PowerShell (Windows) and install the dependencies:

```bash
pip install -r requirements.txt
```

*(Alternatively, install packages directly: `pip install streamlit pandas numpy plotly requests openpyxl python-dateutil`)*

### 3. Launching Applications

#### **Option A: Using 1-Click Interactive Terminal Launcher (Recommended)**

- **macOS / Linux:**
  ```bash
  chmod +x run_all_apps.sh
  ./run_all_apps.sh
  ```
- **Windows:**
  Double-click `run_all_apps.bat` or run from Command Prompt:
  ```cmd
  run_all_apps.bat
  ```

#### **Option B: Running Specific Streamlit Apps Directly**

- **Launch 2050 Master Strategy Web Portal:**
  ```bash
  streamlit run 2050_Master_Strategy_Portal_App.py
  ```
- **Launch Agentic AI Control Tower:**
  ```bash
  streamlit run 2050_Agentic_Control_Tower_App.py
  ```
- **Launch Live Public API Demo Portal:**
  ```bash
  streamlit run 2050_Live_Public_API_Demo_App.py
  ```

---

## 📦 Package Requirements (`requirements.txt`)

```text
streamlit>=1.30.0
pandas>=2.0.0
numpy>=1.24.0
plotly>=5.18.0
requests>=2.31.0
openpyxl>=3.1.0
python-dateutil>=2.8.2
```

---

## 🏛️ Strategic & Regional Context

The applications in this workspace directly support the operationalisation of the **2050 Strategy for the Blue Pacific Continent**, covering:
1. **The 7 Thematic Areas:**
   - **TA1:** Political Leadership and Regionalism
   - **TA2:** People-Centred Development
   - **TA3:** Peace and Security
   - **TA4:** Resource and Economic Development
   - **TA5:** Climate Change and Disasters
   - **TA6:** Ocean and Natural Environment
   - **TA7:** Technology and Connectivity
2. **Monitoring Framework:** 80 Core Outcome Indicators, 28 Regional Collective Actions (RCAs), Washington Group Short Set (WG-SS) GESI disaggregations, and preparation for the **Inaugural 2027 Outcomes Report**.

---

*Developed for the **Pacific Islands Forum Secretariat (PIFS)** and **United Nations Population Fund (UNFPA)** — Data Analytics & Insights Advisory.*
