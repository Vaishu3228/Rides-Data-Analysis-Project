# 🚖 RideIt Driver Engagement & Performance Analysis

Analyzing driver engagement, performance, and cancellation behavior using operational ride data to improve retention, efficiency, and customer experience.

---

## 📌 Project Overview

This project analyzes RideIt's driver engagement, performance, and cancellation behavior using operational ride data. The objective is to identify the factors associated with better driver engagement and recommend business actions to improve **retention**, **operational efficiency**, and **customer experience**.

---

## 🗂️ Dataset Summary

The dataset used for this project is the RideIt Drivers and Driver Activity Dataset. The dataset contains information about:

* Driver Profiles
* Driver Ratings
* Gold Level Count
* Service Type
* Country
* Marketing Participation
* Offers
* Bookings
* Cancellations
* Completed Rides

---

## 🧹 Data Cleaning & Preparation

- Removed **201 duplicate** driver records caused by multi-service registrations
- Replaced missing **Driver Rating** values using mean imputation
- Replaced missing **Gold Level Count** values with `0`
- Standardized data types across both datasets
- Created a **one-to-many relationship** using `driver_id`

---

## 🛠️ Tools & Technologies

* Power BI
* Power Query
* DAX
* Excel

---

## 📊 Business Analysis

1. Measure driver engagement using **Acceptance Rate** and **Ride Completion Rate**
2. Identify factors associated with stronger engagement
3. Compare performance across service types and countries
4. Analyze cancellation behavior and operational efficiency
5. Evaluate the impact of marketing participation and loyalty programs

---

## 📈 Dashboard Development (Power BI)

Developed five interactive dashboard pages:

- **Home Page**
  
  <img width="1407" height="807" alt="Screenshot 2026-08-11 220712" src="https://github.com/user-attachments/assets/df0f4603-b27e-406d-aa90-e4dba4950297" />

- **Driver Engagement Overview**

  <img width="1151" height="650" alt="Screenshot 2026-07-02 210745" src="https://github.com/user-attachments/assets/673b1664-b6ff-47dc-894c-fb788265a915" />

- **Factors Influencing Engagement**

  <img width="1063" height="597" alt="Screenshot 2026-07-04 124556" src="https://github.com/user-attachments/assets/a476d1b9-9bf5-4d9a-9258-6d627d1b375f" />

- **Performance & Cancellation Analysis**

  <img width="1152" height="643" alt="Screenshot 2026-07-02 211127" src="https://github.com/user-attachments/assets/57c7ffa2-c0ff-44b7-a7bd-bed9575065d3" />

- **Insights & Recommendations**

  <img width="1150" height="647" alt="Screenshot 2026-07-02 212418" src="https://github.com/user-attachments/assets/94c1f60f-538a-4be1-bd90-0affd99c61a8" />

---

## 🔑 Key Insights

- Ride Completion Rate remained **above 80%**
- Acceptance Rate remained around **28–30%**
- Highly rated drivers completed more rides
- Drivers with higher Gold Level counts showed stronger engagement
- Marketing participation positively influenced ride activity
- Passenger cancellations exceeded driver cancellations

---

## 💡 Business Recommendations

- Increase acceptance rates through incentives
- Reduce cancellations through alerts and improved matching
- Expand marketing campaigns to inactive drivers
- Strengthen loyalty programs and Gold benefits

---

## 🎯 Business Impact

Expected impact includes improved driver engagement, higher completion rates, lower cancellations, better customer experience, and increased driver retention.

---

## 👩‍💻 Author

**Mallayolla Vaishnavi**


