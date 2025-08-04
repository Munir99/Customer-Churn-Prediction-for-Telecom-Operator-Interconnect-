# Customer-Churn-Prediction-for-Telecom-Operator-Interconnect-

## Final Project: Telecom Churn Prediction

This project focuses on predicting customer churn for **Interconnect**, a telecom operator. If a customer is predicted to leave, they can be proactively offered promotional deals and customized plans to improve retention.

---

### Interconnect's Services

The company offers the following:

- **Landline Communication**: Ability to connect several lines simultaneously.
- **Internet**: Delivered via DSL (digital subscriber line) or fiber optic cable.
- **Additional Services**:
  - **DeviceProtection** – Antivirus software
  - **OnlineSecurity** – Malicious website blocker
  - **TechSupport** – Dedicated support line
  - **OnlineBackup** – Cloud storage and data backup
  - **StreamingTV** – TV streaming service
  - **StreamingMovies** – On-demand movie service

Customers can choose from different contract types (monthly, 1-year, or 2-year) and payment methods. Electronic invoices are available.

---

### Data Description

The dataset includes client information from four CSV files:

- `contract.csv` — contract details  
- `personal.csv` — personal data  
- `internet.csv` — internet service usage  
- `phone.csv` — phone service usage  

All files include a `customerID` column to uniquely identify clients.

📅 **Note**: The contract data is valid as of **February 1, 2020**.

📂 Dataset location: `/datasets/final_provider/`

---

### Target & Metrics

- **Target feature**: `EndDate` = `'No'` (i.e., customer is still active)
- **Primary evaluation metric**: **AUC-ROC**
- **Secondary metric**: **Accuracy**

---

### Assessment Criteria

| AUC-ROC Range           | Score |
|-------------------------|-------|
| < 0.75                  | 0 SP  |
| 0.75 – 0.80             | 4 SP  |
| 0.81 – 0.84             | 4.5 SP|
| 0.85 – 0.86             | 5 SP  |
| 0.87 – 0.87             | 5.5 SP|
| ≥ 0.88                  | 6 SP  |

---

📥 You can download the dataset using the platform or locate it under `/datasets/final_provider/`.

