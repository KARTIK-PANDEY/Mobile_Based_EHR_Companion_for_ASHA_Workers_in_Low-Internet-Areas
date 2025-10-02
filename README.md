# Mobile-based EHR Companion for ASHA Workers (Low Internet Areas)

**Smart India Hackathon 2025 — Problem Statement ID: SIH25219**  
**Theme:** MedTech / BioTech / HealthTech  
**Team Name:** Hack Slayer  

---

## 📌 Overview
The **Mobile-based EHR Companion** is designed to empower **ASHA workers** and **Primary Health Centre (PHC) staff** in rural and low-internet regions.  
It enables secure **offline-first data collection**, **automatic synchronization**, and **multilingual Language + voice support** to reduce paperwork, minimize errors, and improve patient outcomes.  

---

## 🎯 Problem Statement
ASHA workers face challenges in recording, maintaining, and transmitting patient health records due to:
- Poor or no internet connectivity in rural areas.  
- Heavy paperwork and manual processes leading to errors.  
- Delays in reporting and lack of real-time health data visibility.  

---

## 💡 Proposed Solution
Our **Smart Health Companion App** supports:
- ✅ **Offline-first design** with data syncing once connectivity is available  
- ✅ **Voice input & multilingual support** for ease of use  
- ✅ **Timely reminders** for ANC check-ups, vaccination schedules & follow-ups  
- ✅ **Role-based dashboards** for ASHA workers and PHC staff  
- ✅ **Integration with ABDM / NDHM (Health ID)** for interoperability  

---

## 🚀 Features
- **Offline Data Entry:** Works seamlessly in low/no internet conditions.  
- **Multilingual & Voice Input:** User-friendly for ASHA workers in local languages.  
- **Auto-Sync Engine:** Synchronizes securely when internet is restored.  
- **Reminders & Notifications:** For vaccination, maternal care, and follow-ups.  
- **Real-Time PHC Dashboards:** Supervisors get instant visibility into rural health data.  
- **Reduced Paperwork:** Digital registers save ~5 hours/week for each ASHA worker.  

---

## 🏗️ Technical Approach

**Tech Stack:**
- **Frontend (Mobile):** React Native (cross-platform, offline-first)  
- **Backend:** FastAPI (Python), REST APIs  
- **Database:** Secure local SQLite (mobile) + Central DB with sync service  
- **Offline Sync Engine:** Handles queue-based data synchronization & conflict resolution  
- **Integration:** ABDM/NDHM Health ID compliance  

**App Workflow:**  
1. Data entered offline by ASHA worker  
2. Stored securely in local DB  
3. Auto-sync triggered once internet is available  
4. Data accessible to PHC staff in real-time dashboard  

---

## 📊 Feasibility & Viability
- **Coverage:** One PHC app supports ~20,000 villagers  
- **Efficiency:** Saves ~30% ASHA documentation time, reduces errors by 35%  
- **Impact:** Improves ANC & vaccination adherence by 25–30%, reduces missed visits by 35%  
- **Training:** Half-day digital training sufficient for ASHA workers  
- **Cost:** ₹5–7 lakh per PHC (pilot) — scalable nationwide  
- **Regulatory:** Compliant with ABDM/NDHM standards  

---

## 🌍 Impact & Benefits
- **⏱ Time Savings:** ASHA workers save ~5 hours/week  
- **📉 Error Reduction:** Auto-validation reduces manual errors by ~40%  
- **📡 Real-Time Visibility:** PHC staff efficiency improves by ~30%  
- **👶 Better Health Outcomes:** ANC/vaccination adherence +25–30%  
- **📑 Reduced Paperwork:** Eliminates manual registers  
- **📊 Structured Data:** Clean records for decision-making & policy planning  
- **🔗 Integration Ready:** Scalable to ABDM/NDHM health platforms  


---

## 📖 References
- Varshney, P. et al. *Role of ASHAs in Indian public mental healthcare*, JFMPC 2022  
- Mahmood, H. et al. *mHealth approaches for improving caregiver knowledge*, J Global Health 2020  
- Garg, P. K. et al. *ASHA worker awareness in rural Haryana*, NJCM 2013  
- Gopalakrishnan, L. et al. *ASHA + Anganwadi counseling and maternal outcomes*, PLOS Global Public Health 2024  
- UNICEF Annual Report 2020 – Primary healthcare in remote India  
- NITI Aayog – *Investment Opportunities in India’s Healthcare Sector*  
- WHO Guidelines & National Health Mission (NHM), India  

---

## 🤝 Contributing
We welcome contributions!  
1. Fork the repository  
2. Create a feature branch
3. Commit changes and push  
4. Open a Pull Request
5. create pull Request

---

## 📜 License
This project is licensed under the **GNU General Public License v3.0**. See [LICENSE](LICENSE) for details.  

---

