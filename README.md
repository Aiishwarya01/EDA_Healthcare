## 📊 Medical Appointments Analysis

This project explores a medical appointments dataset to analyze **factors influencing whether a patient shows up** for their appointment. The goal is to derive actionable insights that can help healthcare providers improve patient turnout and operational efficiency.

---

## 📁 Dataset

- The dataset contains records of **over 110,000 medical appointments** in Brazil.
- Each record includes patient details such as age, gender, SMS reminders, medical conditions, appointment day, and whether the patient showed up.

---

## 🎯 Objective

- Understand the key factors that influence patient **no-shows**.
- Analyze demographic and medical attributes to uncover **patterns and trends**.
- Provide **data-driven insights** to improve appointment attendance.

---

## 🧪 Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**,
- **Seaborn**
- **Jupyter Notebook**

---

## 🔍 Exploratory Data Analysis (EDA)

### ✅ Key Cleaning Steps
- Converted `ScheduledDay` and `AppointmentDay` to datetime objects.
- Renamed and standardized column names.
- Removed irrelevant features like `PatientId`, `AppointmentID`, and `Neighbourhood`.

### 📊 Visualizations and Insights

1. **Gender Distribution**
   - Female patients scheduled **more appointments** than male patients.

2. **Age-wise Attendance**
   - **Show and no-show rates were nearly equal** across most age groups.
   - Notable exception: **Patients aged 0 and 1** had a **higher show-up rate (~80%)**.

3. **Neighbourhood Trends**
   - All neighbourhoods show a **consistent show-up rate of ~80%**.

4. **Scholarship Impact**
   - **Non-scholarship patients** (99,666) had an **80% show rate**.
   - **Scholarship recipients** (21,801) showed up **75% of the time**.

5. **Hypertension & Diabetes**
   - Patients with **hypertension (85%)** and **diabetes (83%)** had **higher attendance** rates than those without.

6. **SMS Reminders**
   - Surprisingly, **patients who did not receive SMS reminders** had a **higher attendance rate (84%)** than those who did (72%).

7. **Weekday Appointments**
   - **No appointments were scheduled on Sundays.**
   - **Very few appointments on Saturdays** compared to weekdays.

---

## 🧠 Findings Summary

- **Age, medical conditions, and SMS reminders** play varying roles in patient attendance.
- **SMS reminders may need improvement** or personalization, as they did not correlate with higher show-up rates.
- The data can help hospitals **identify high-risk no-show profiles** for better appointment planning and resource allocation.

---

## 📬 Contact

**Aishwarya SR**  

📧 aishwaryasr097@gmail.com 

🔗 [LinkedIn](https://www.linkedin.com/in/aishwarya-sr/)  

💻 [GitHub](https://github.com/Aiishwarya01)





