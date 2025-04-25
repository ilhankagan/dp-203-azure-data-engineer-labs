# Lab 19 - Integrate Azure Stream Analytics with Power BI

## 🧠 Objective
In this lab, I integrated **Azure Stream Analytics** with **Power BI** to visualize real-time streaming data from **Event Hub**.

---

## ⚙️ Key Steps

### 1. **Deploying Azure Stream Analytics Job**
I created a new Stream Analytics Job named `stream-orders`. This job reads events from Event Hub and outputs them to a Power BI dataset.

📸 ![Stream Analytics Deployment](images/lab19/streamdeployment.PNG)

---

### 2. **Adding Input: Event Hub**
Configured `orders` input as **Stream type** from an Event Hub instance to stream incoming event data into the job.

📸 ![Input Setup](images/lab19/inputadd.PNG)

---

### 3. **Adding Output: Power BI**
Configured the output to **Power BI** with alias `powerbi-dataset` using **user token** for authentication.

📸 ![Output Setup](images/lab19/outputadd.PNG)

---

### 4. **Power BI Dataset Verification**
The streaming dataset `realtime-data` appeared in the Power BI workspace `mslearn-streaming`.

📸 ![Power BI Streaming Dataset](images/lab19/powerBI.PNG)

---

### 5. **Realtime Dashboard Creation**
Built a live dashboard named `Order Tracking` to monitor real-time order counts using the `ENDTIME` field.

📸 ![Power BI Dashboard](images/lab19/powerBIvis.PNG)

---

### 6. **Power BI Workspace Overview**
Confirmed the availability of both the dataset and the dashboard inside the workspace.

📸 ![Power BI Workspace](images/lab19/powerBıwspace.PNG)

---

## ✅ Skills Practiced

- Azure Stream Analytics job creation
- Configuring Event Hub as a stream input
- Streaming output to Power BI
- Real-time dashboard creation

---

## 🧩 Technologies Used

| Service               | Description                                  |
|-----------------------|----------------------------------------------|
| Azure Stream Analytics| Real-time data processing                    |
| Azure Event Hub       | Ingesting event streams                      |
| Power BI              | Visualization of live streaming data        |

---

## 📌 Notes

> ⚠️ Stream Analytics Power BI output will be deprecated on **October 31, 2027**. Consider alternate output sinks for long-term projects.

---

## 📁 Folder Structure

