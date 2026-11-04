# DoseWindow on PharmEasy — Mobile Prototype & Web Showcase

Interactive prototype for **DoseWindow** integrated into **PharmEasy**, created for **ProdVerse (Theme 01: Everyday Wellbeing)** by **Team Garde Impériale**.

---

## 💡 The Core Problem & USP
> *"PharmEasy sells him the strip. Nobody watches what happens after it is opened."*

While PharmEasy excels at medicine delivery, it stops at the doorstep. **DoseWindow** adds the missing post-delivery care layer:
- **Prescription to Dose Schedule**: meal-anchored windows with 1-tap/wrist logging.
- **Commercial Loop**: Day 19 of 30 strip countdown with 1-tap re-order on PharmEasy.
- **The 3×3 Safety Rule (Hero Feature)**:
  - **3A:** Measure 3 times with a validated Bluetooth cuff (1 min apart, average last two).
  - **3B:** Immediate 3-channel alert (Push → SMS → Automated Voice Call) stopping on acknowledgment.
- **Ambulance Handover**: 108 Emergency + nearest hospital preset by pincode.
- **The Appointment Page**: A 1-page clinical brief for the doctor revealing the moat: *"BP elevated this week. Also missed 3 morning doses."*

---

## 🚀 How to Run the Showcase

### Option 1: Direct in Browser
Simply open [index.html](file:///C:/Users/singh/.gemini/antigravity/scratch/dosewindow-prototype/index.html) in Chrome, Edge, or Safari.

### Option 2: Run with Node.js
```bash
cd C:\Users\singh\.gemini\antigravity\scratch\dosewindow-prototype
node server.js
```
Then visit: `http://localhost:3001`

---

## 📱 5 Interactive Screens in the Prototype
1. **PharmEasy Home Screen**: Authentic PharmEasy UI (with your uploaded screenshot) featuring the new integrated **DoseWindow Active Care Card**.
2. **Dose Matrix & Strip Refill**: Today's 4 dose slots, swipe/tap to log, skip with reason, and PharmEasy strip replenishment.
3. **The 3×3 Emergency Alert Engine**: Live simulation of Sunday 9:12 PM BP spike (178/104 mmHg), 3-bar measurement, and simultaneous 3-channel dispatch.
4. **Caregiver's Phone Reception**: Shows what the daughter/caregiver sees in real time, with the *"I'm calling him"* alert-halting button and 108 Ambulance handover.
5. **Doctor's Appointment Page**: The 1-page clinical summary artifact that saves the 8-minute consultation.
