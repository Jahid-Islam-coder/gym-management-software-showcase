# Gym Management System — Case Study & Project Showcase

> **Note:** The underlying codebase for this software is private and proprietary. This repository serves as a technical case study, feature demonstration, and architectural overview.

---

## 📌 Project Overview
A comprehensive, full-stack gym management platform designed to streamline member check-ins, automated subscription billing, class scheduling, and administrative reporting.

Project Name | Trainer – End-to-End Gym Operations & Member App

- **Role:** Lead Developer (Full-Stack / Architecture / UI/UX)

- Responsibilities: Architected the end-to-end system to handle concurrent member check-ins, real-time database sync, and high-availability operations in active production. Designed custom workflows for gym staff and active members.
  
- **Target Audience:** Gym owners, front-desk staff, and active members.
  
- **Status:** In Active Production / Deployed



## Problem
The gym was experiencing three main challenges in managing its members and payments:

1. **Daily payment tracking and payment disputes**

Daily members were charged a fixed ৳30 for each visit. However, payments were recorded manually in a diary, making it difficult to reliably verify whether a member had actually paid.
This led to frequent payment disputes. A member could claim that they had already paid, while the manager had no written record of the transaction. Without a reliable payment history, it was difficult for the gym owner to verify the claim and prevent missed or disputed payments.

2. **Monthly subscription management**

Keeping track of monthly members, subscription end dates, and upcoming renewals was becoming difficult. The owner needed a clearer way to identify which memberships were active, expiring, or required renewal.

3. **Paper-based management**

Relying on regular paperwork for member records, visits, and payment tracking made everyday gym management slower and harder to maintain.


## Solution
The Trainer App replaces the gym's paper-based member and payment management with a centralized digital system.

1. **Reliable tracking system to prevent profit leakage**

When members attend the gym, their visit and payment status are digitally tracked. the gym manager/admin uses the simple visit button to record their visit and quickly classifies them as unpaid members. When they clear daily payments, the manager/admin taps the payment button, removing the members from the unpaid section. This provides the manager with a complete payment history for each member, avoids disagreements caused by missing or confusing diary records, and essentially eliminates gym earnings leakage.

2. **Simplified monthly subscription management**
   
Monthly members can be registered with their subscription period and tracked through the app. The manager can view membership status, monitor subscription end dates, and manage renewals without relying on manual records.

3. **Centralized member management**
   
Member records, visits, payments, and subscription information are stored in one system using Flutter and Firebase. The dashboard provides an overview of important gym metrics, helping the manager manage daily operations more efficiently while eliminating the daily manual paper work.



## 📸 Screenshots & Demos
| Dashboard Overview |
![Dashboard](screenshots/individual/dashboard.png)




| Member Check-In Flow |
![Check-In](screenshots/individual/daily-members.png)



## 🛠️ Tech Stack & System Architecture

### Frontend
- **Framework:** [Flutter]
- **State Management:** [setState]
- **Styling/UI:** [Custom UI components, fl_chart]

### Backend & Infrastructure
- **Language/Runtime:** [Dart]
- **Database:** [Firebase Firestore]
- **Authentication:** [Firebase Auth]



### System Architecture Diagram
![System Architecture](architecture/trainer-app-architecture.png)
