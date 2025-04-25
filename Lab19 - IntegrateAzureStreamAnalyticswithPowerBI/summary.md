# 🚀 Lab 19 - Integrate Azure Stream Analytics with Power BI

> [Lab 19 Instructions]([https://github.com/MicrosoftLearning/dp-203-azure-data-engineer/blob/master/Instructions/Labs/19-Integrate-Azure-Stream-Analytics-with-Power-BI.md](https://github.com/secedit/dp-203-azure-data-engineer/blob/master/Instructions/Labs/19-Stream-Power-BI.md))

## 🛠️ What I Did

### 1. Created and Deployed Stream Analytics Job
- Deployed a **Stream Analytics Job** named `StreamAnalyticsJob`.
- Resource group and job name were confirmed after successful deployment.
- ✔ Deployment status: `OK`
- 📸 *Screenshot:* `streamdeployment.PNG`

### 2. Configured Event Hub Input
- Added input from an **Event Hub** named `orders`.
- Confirmed `Source type` as **Stream** and `Type` as **Event Hub**.
- 📸 *Screenshot:* `inputadd.PNG`

### 3. Configured Power BI Output
- Configured **Power BI** as output under alias `powerbi-dataset`.
- Used **User token** as authentication mode.
- 📸 *Screenshot:* `outputadd.PNG`

### 4. Connected to Power BI Workspace
- Verified new dataset `realtime-data` and dashboard `Order Tracking` appeared under the correct workspace.
- 📸 *Screenshot:* `powerBıwspace.PNG`

### 5. Created Realtime Visualization in Power BI
- Created a Power BI chart showing **real-time order count** by end time.
- Dashboard updated in real time as new events were streamed.
- 📸 *Screenshot:* `powerBIvis.PNG`

### 6. Final Workspace Overview
- Reviewed all workspace components under `mslearn-streaming`, including dashboards and datasets.
- 📸 *Screenshot:* `powerBI.PNG`

---

✅ **Completed** Lab 19 successfully and gained experience in:
- Integrating Azure Stream Analytics with Power BI
- Streaming data pipeline configuration
- Visualizing real-time data in Power BI dashboards


