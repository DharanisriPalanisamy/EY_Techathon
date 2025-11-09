# EY_Techathon
**EY Techathon 6.0  Challenge 3: Autonomous Predictive Maintenance and Proactive Service Scheduling**

**Agentic AI for Predictive Vehicle Maintenance**

**Project Overview:**

This project focuses on developing an intelligent vehicle maintenance system that predicts possible mechanical and electrical failures before they happen.
The solution uses an Agentic AI framework, where multiple AI agents work together to analyze data, predict issues, interact with users, and schedule maintenance automatically.
It aims to reduce unplanned breakdowns, improve customer satisfaction, and create a continuous feedback loop between the service and manufacturing teams.

**System Architecture:**

The system is built around a Master Agent that coordinates the following worker agents:

**Data Analysis Agent**          – Processes real-time sensor data and maintenance logs.

**Diagnosis Agent**              – Detects anomalies and predicts fault types.

**Customer Engagement Agent**    – Sends alerts through chatbot or voice assistant.

**Scheduling Agent**             – Books or suggests service appointments automatically.

**Manufacturing Insights Agent** – Analyses recurring faults and provides RCA/CAPA feedback to improve product design.

**Tech Stack:**
| Component   | Technology                                                          |
| ----------- | ------------------------------------------------------------------- |
| Programming | Python (Colab Environment)                                          |
| Libraries   | Pandas, NumPy, Matplotlib                                           |
| Dataset     | New Energy Vehicles Dataset (Kaggle) + Synthetic Data               |
| Interaction | Chatbot and Voice Alert Simulation                                  |
| Output      | Fault Prediction, Severity Classification, Scheduling, RCA Insights |

**Key Features:**

Data driven fault prediction using dynamic thresholds.

Identification of multiple fault types such as **battery, motor, oil, brake, and suspension issues.**

Health score calculation and severity-based classification.

AI-based **voice and text alerts** for vehicle owners.

**Automatic service slot** generation for critical faults.

Root Cause Analysis (RCA) and CAPA **feedback loop** to manufacturing.

**Sample Results:**

Predicted Faults: Engine Overheating, Low Oil Level, Brake Fault, Chain Imbalance

Severity Levels: Low / Medium / High

Health Score: 0–100%

**Example AI Alert:**

Vehicle VEH_008: Engine Overheating Detected.  

Voice Agent: “A service slot has been booked for tomorrow at 10 AM.”  

**Visuals:**

Pie chart showing severity distribution

Bar chart for vehicle health scores

 **Workflow Summary:**

Vehicle Sensor Data  
      ↓  
Predictive Maintenance Logic  
      ↓  
Fault Detection and Severity Analysis  
      ↓  
AI Alerts and Auto Scheduling  
      ↓  
RCA/CAPA Feedback to Manufacturing

**Future Scope:**

Integrate real-time IoT sensor data using OBD-II or CAN bus.

Develop a complete dashboard for fleet monitoring.

Add ML-based failure prediction models.

Integrate voice assistant with real API (Twilio or Alexa SDK).

**Notebook Link:**

[Click here to open the notebook](https://github.com/DharanisriPalanisamy/EY_Techathon/blob/main/ey.ipynb)

**Team Information:**

**Team Name: Cogniflow**

**Members:** 

Dharani Sri P

Aksheta S

Dharanika V

Madhavan S

Srinithi S

**Domain:** Electronics and Communication Engineering

**Institute:** **PSG Institute of Technology and Applied Research**

**License:**

This project is for academic and educational use only.
