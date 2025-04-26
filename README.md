# Partner Onboarding EDM Automation Flow (Abstracted Real Project)

This project was inspired by a real-life onboarding automation flow, which I helped design as part of my role at a financial services company.  
While specific internal structures, data, and CRM configurations are confidential, this public version presents a generalised structure to demonstrate the approach and logic behind scalable onboarding automation using CRM triggers and EDM strategies.

**This EDM flow is designed for newly onboarded IB partners**, guiding them through each critical step of the onboarding process and helping maximise engagement early on.

---

## 📈 Overview

- Simulated the onboarding journey from partner account creation to long-term engagement milestones.
- Built an EDM automation tree based on CRM-recorded actions, agreements, and partner behaviour within the first month.
- Used Mermaid.js to visualise the flow for better documentation and scalability.
- Designed with modular CRM triggers to support conditional email logic based on real engagement activities.

---

## 🧠 Background and Project Intent

In the financial services and partner sales industry, it is common for some partners to become inactive over time due to various internal and external factors.  
Addressing partner inactivity and maintaining healthy engagement levels are critical for organisations.

This EDM automation project was initiated to proactively guide new partners through their first month of onboarding. It provides timely answers to common questions and reinforces engagement through milestone-based communications.  
By analysing the first month’s behavioural data (e.g., agreement status, referral activities, portal usage), partners showing active engagement are nurtured further through this flow.

Partners not reaching the desired activity levels within the first month will be transitioned into a separate re-engagement system designed explicitly for inactive partners.  
This two-tiered approach maximises operational efficiency, personalises partner communications, and minimises long-term churn risk.

---

## 🛠️ Technologies Used

- **Mermaid.js**: Visualising onboarding workflows and automation trees.
- **Markdown**: Structuring documentation.
- **(Optional) JavaScript (pseudo-code)**: Simulating CRM event-based logic.

---

## 🧩 Flow Structure Highlights

- 📌 CRM reflects new partner account → triggers a "Welcome & Agreement Check" email.
- 📌 Agreement completion → triggers partner portal usage guide.
- 📌 Milestone-based automated messages (7 days, 1 month, etc.) guide early engagement.
- 📌 Referral achievement triggers personalised congratulations emails.
- 📌 Inactivity or low engagement after 1 month triggers transition to a re-engagement flow.
- 📌 Birthday automation included for personalised engagement.

*(Detailed flow available in the `flowchart.mmd`.)*

---

## 🚀 Purpose and Key Learnings

- Translate real-life business logic into scalable onboarding workflows.
- Apply CRM-based conditions to control customer lifecycle automation.
- Strengthen visualisation and documentation skills for system design.
- Demonstrate cross-functional thinking across CRM, marketing, and ops.

---

## 📎 Notes

- All data and structures in this project are fictional and abstracted from real scenarios.
- No actual customer or company data is included.
- This version is safe for public sharing and generalised across industries.

---

## ✨ Next Steps

- Build a re-engagement EDM system specifically for inactive partners.
- Extend the onboarding logic to multi-channel communication (SMS, push notifications).
- Develop analytics to measure conversion across lifecycle touchpoints.
