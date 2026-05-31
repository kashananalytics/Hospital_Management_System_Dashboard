# Hospital_Management_System_Dashboard
🏥 Interactive HMS Analytics Dashboard | HTML · JS · Python · Chart.js | 1,500 Patients · 400 Doctors · ₨ 109.8M Revenue | Built with AI
# 🏥 Hospital Management System — Interactive Analytics Dashboard

> Built with the assistance of AI (Claude by Anthropic). The data, structure, decisions, and project ownership are entirely mine. I believe in being transparent about the tools I use.

![Dashboard](https://img.shields.io/badge/Dashboard-Interactive-2a7f7f?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![AI Assisted](https://img.shields.io/badge/AI%20Assisted-Claude%20by%20Anthropic-blueviolet?style=for-the-badge)

---

## 📌 Project Overview

A fully interactive, multi-section analytics dashboard built on a real-world Hospital Management System (HMS) dataset. The dashboard visualizes KPIs, trends, and operational metrics across **8 departments** using clean, neutral HMS-themed colors.

---

## 📊 Dataset Summary

| Entity | Count |
|---|---|
| Patients | 1,500 |
| Doctors | 400 |
| Nurses | 500 |
| Helpers | 1,100 |
| Departments | 31 |
| Total Beds | 500 |
| Total Rooms | 391 |
| Wards | 63 |
| Appointments | 1,000 |
| Medical Records | 3,000 |
| Surgeries | 1,000 |
| Bed Admissions | 1,000 |
| Room Admissions | 1,000 |
| Staff Shifts | 2,058 |
| **Total Revenue** | **₨109.8M** |

---

## 🗂️ Dashboard Sections

### 📊 1. Hospital Overview
- 8 top-level KPI cards (patients, doctors, beds, revenue, departments, surgeries, records)
- Monthly appointment trend (12-month line chart)
- Appointment status donut (Completed · No-Show · Scheduled · Cancelled)
- Payment methods bar chart
- Booking mode breakdown
- Top visit reasons with progress bars

### 👥 2. Patient Analytics
- Gender distribution (790 Female · 710 Male)
- Age group distribution (Child · Teen · Adult · Middle · Senior)
- Grouped age-by-gender comparison chart

### 📅 3. Appointments
- Completion rate: **76.9%** | Cancellation: **4.3%** | No-Show: **10.2%**
- Average payment: ₨1,663 | Total: ₨1.66M
- Monthly bar chart with peak highlights
- Payment method pie chart
- Booking channels (Online · In Person · Call)
- Horizontal bar of top appointment reasons

### 🩺 4. Medical Records
- 3,000 records analyzed
- Top diagnoses bar chart
- Diagnosis share donut (excluding General Checkup)
- Most frequent conditions: Migraine, Hypertension, Angina, Asthma

### ⚕️ 5. Surgery Records
- 1,000 total surgeries
- Top 10 surgery types (horizontal bar)
- Post-operative outcome donut:
  - Need Special Care: 223
  - Transfer to ICU: 213
  - Visit Next Month: 202
  - Recovered: 188
  - Stable: 174

### 👨‍⚕️ 6. Staff Overview
- 2,000 total staff (400 Doctors · 500 Nurses · 1,100 Helpers)
- Role composition donut
- Doctor gender ratio (261 Male · 139 Female)
- 2,058 scheduled shifts
- Workforce ratio cards (Nurse:Doctor · Helper:Doctor)

### 🛏️ 7. Beds & Rooms
- 500 beds across 63 wards
- 391 rooms across 6 types (Consultation · Super Deluxe · Deluxe · Standard · Emergency · Operation Theatre)
- Average stay: 3.47 days | Max: 9 days
- Average bed billing: ₨36,061
- Bed payment methods donut
- Ward type progress bars

### 💰 8. Revenue Analytics
- Total revenue: **₨109.8M**
- Room Revenue: ₨72.1M (65.6%)
- Bed Revenue: ₨36.1M (32.8%)
- Appointment Revenue: ₨1.66M (1.5%)
- Revenue stream donut chart
- Room vs Bed payment method comparison

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Dashboard structure & layout |
| CSS3 (custom variables) | Styling, theming, responsive design |
| JavaScript (Vanilla) | Interactivity, navigation, chart rendering |
| Chart.js 4.4.1 | All charts (bar, line, doughnut) |
| Python 3 + pandas | Data extraction & KPI computation from .xlsx |
| Google Fonts (DM Sans + DM Serif Display) | Typography |
| AI — Claude by Anthropic | Development assistance |

---

## 🎨 Design System

Color palette chosen to reflect a **neutral, professional HMS aesthetic**:

| Role | Color |
|---|---|
| Primary (Teal) | `#2a7f7f` |
| Secondary (Slate) | `#3e5771` |
| Success (Sage) | `#5a8a6a` |
| Warning (Amber) | `#c47a30` |
| Alert (Rose) | `#a05060` |
| Background | `#f0f4f8` |
| Surface | `#ffffff` |

---

## 🚀 How to Run

1. Open the URL:
https://kashananalytics.github.io/Hospital_Management_System_Dashboard/
2. Open `HMS_Dashboard.html` in any modern browser.
3. No server, no installation, no dependencies — works offline.

---

## 🤖 AI Disclosure

This project was developed **with the assistance of Claude by Anthropic**. AI was used to help with data extraction, chart logic, layout structure, and code generation. All data, project decisions, and ownership belong to me. I believe transparency about AI tooling is a professional standard worth keeping.

---

## 📜 License

MIT License — free to use, modify, and distribute with attribution.
