<div align="center">
  <img src="logo.png" alt="WFM AI Assistant Logo" width="300" />
  <h1>WFM AI Assistant</h1>
  <p><b>Your AI Partner for Call Center Workforce Management</b></p>
  
  <p>
    <a href="README_zh.md">中文文档</a> •
    <a href="#features">Features</a> •
    <a href="#quick-start">Quick Start</a> •
    <a href="#capabilities">Capabilities</a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License" />
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome" />
  </p>
</div>

---

## 🌟 Introduction

WFM AI Assistant is a specialized AI agent designed for Workforce Management (WFM) and Real-Time Analysts (RTA) in call centers. It automates the entire closed-loop operation of workforce management, including traffic forecasting, scheduling strategy, real-time dispatch, data reporting, attendance management, and recruitment alerts.

**Core Principle: System Agnostic & Data Driven**
- **System Integration**: Directly read API data streams from platforms like Genesys, NICE, or custom CRM systems.
- **Manual Mode**: No system? No problem. Upload Excel/CSV files, and the AI will handle all calculations and decision recommendations.
- **Human-in-the-loop**: The AI handles the heavy lifting of calculations, while human specialists focus solely on **judgment and approval**.

## ✨ Key Features

- 📈 **Traffic Forecasting**: Analyzes historical data, business dynamics (marketing, holidays), and external factors to dynamically predict call volumes.
- 📅 **Smart Scheduling**: Balances AI/human resources, optimizes shift structures (half-hour granularity), and ensures healthy workload distribution.
- ⚡ **Real-Time Operations (RTA)**: 24/7 monitoring of Service Level (SL), Average Handling Time (AHT), queuing, and agent status.
- 🚨 **Automated Alerts**: Triggers real-time alerts for SL drops, agent overload, and generates emergency dispatch plans for sudden absences or weather events.
- 📊 **Automated Reporting**: Extracts metrics from raw communication logs (ACD, Hold, ACW) and highlights anomalies instantly.

## 🚀 Quick Start

### Mode A: API Integration (Fully Automated)
Configure the system to continuously push data. The AI will calculate metrics in real-time and automatically alert you when thresholds are breached.

### Mode B: File Upload (Semi-Automated)
Simply upload an `.xlsx`, `.csv`, or a screenshot. The AI will instantly:
1. Identify column structures without manual mapping.
2. Calculate all possible KPIs.
3. Highlight anomalies.
4. Provide actionable recommendations.

## 🧠 AI Capabilities Map

| Module | Description | Data Required |
|--------|-------------|---------------|
| **Forecasting** | Predicts call volume with confidence intervals and suggested headcount. | Historical volume data (≥ 4 weeks) |
| **Real-time Monitoring** | Calculates SL, AHT, and utilization. Alerts on SLA breaches. | Agent status & traffic data |
| **Break Optimization** | Calculates safe break windows and generates batch recommendations. | Current headcount, volume, target SL |
| **Emergency Dispatch** | Handles sudden absences and generates contingency plans. | Roster, absences, employee records |
| **Data & Anomalies** | Scans reports for missing data, excessive handling time, or capacity limits. | Any operational data report |
| **Attendance & HR** | Checks shift swaps, calculates attendance, and alerts for hiring needs. | Clock-ins, rosters, swap requests |

## 🤝 Human-AI Collaboration

```text
Data Input (Excel / API)
        ↓
   [AI] Calculates + Detects Anomalies + Generates Solutions
        ↓
   [WFM Specialist] Evaluates + Approves (30 seconds to decide, not 30 minutes to calculate)
        ↓
   [AI] Drafts Notifications + Logs Actions + Updates Schedules
        ↓
   [Agents] Execution
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
