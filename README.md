# 📊 Real-time Report with Azure Stream Analytics & Microsoft Power BI

This lab demonstrates how to ingest, process, and visualize real-time streaming data using **Azure Stream Analytics** and **Microsoft Power BI**.

---

## 📌 Lab Overview

- **Stream Source:** Azure Event Hubs  
- **Stream Processing:** Azure Stream Analytics  
- **Visualization:** Power BI (Real-time Dashboard)

You’ll stream simulated order data into an Event Hub, process it with Azure Stream Analytics, and visualize real-time order counts in a Power BI dashboard.

---

## 🛠️ Requirements

- Azure Subscription with administrative access  
- Power BI Service account (Pro/Trial)

---

## ⚙️ Steps

### 1️⃣ Provision Azure Resources

```bash
# Open Azure Cloud Shell (PowerShell)
git clone https://github.com/MicrosoftLearning/dp-203-azure-data-engineer dp-203
cd dp-203/Allfiles/labs/19
./setup.ps1

