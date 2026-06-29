# Shramik Sakshi 🛠️
### Empowering the Unorganized Workforce with Digital Wage Protection

Shramik Sakshi is an automated wage protection and attendance verification system designed for the unorganized labor sector. By leveraging simple technology—WhatsApp and GPS—we provide laborers with an immutable "Digital Receipt" for every day of work, ensuring they have the proof needed to fight wage theft.

---

## 💡 The Problem
Millions of daily wage laborers face the constant risk of "wage theft," where contractors deny they worked specific days or withhold payments without evidence. Existing solutions require apps, smartphones, and digital literacy that the average laborer often lacks.

## 🚀 The Solution
**Shramik Sakshi** removes barriers. No app to install. No registration forms.
1. **Attendance:** A laborer sends their location via WhatsApp.
2. **Verification:** The system generates an immediate, timestamped digital receipt.
3. **Transparency:** An NGO Dashboard tracks work history, providing a ledger that can be presented during labor disputes.

---

## 🛠️ Tech Stack
- **Backend:** Python (FastAPI)
- **Database:** Supabase (PostgreSQL)
- **Messaging:** Twilio API for WhatsApp
- **Frontend/Dashboard:** Streamlit (Cloud-hosted)
- **Version Control:** Git & GitHub

---

## 📋 Demo Instructions for Judges
*We recommend watching our 90-second walkthrough before testing live.*

**1. Watch the Demo:**
[🔗 View Demo Video Here] 

**2. Test the Live Integration:**
To interact with the bot:
1. Open the [Shramik Sakshi Dashboard](https://shramik-sakshi.streamlit.app/).
2. In the sidebar, look for the **"Chat with Bot"** button.
3. Once in WhatsApp, send the message: `join [YOUR_SANDBOX_CODE]` (found in the sidebar).
4. Once connected, send a **Location Pin** to log your attendance.
5. Send **"Hisaab"** to get your total earnings report.

---

## 📊 Features
- **Immutable Receipts:** Every location pin generates a verification token stored in our secure SQL database.
- **Automated Calculations:** Logic handles daily wage multiplication to prevent manual accounting errors.
- **NGO Command Center:** A live-updating map and table allows unions and NGOs to track worker deployment and flag wage discrepancies in real-time.
- **Zero-Barrier UX:** Built for WhatsApp, the most commonly used communication tool in the sector.

---

## 💻 Local Setup
If you would like to run this project locally:

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/s-kunwar/shramik-sakshi.git](https://github.com/s-kunwar/shramik-sakshi.git)
   cd shramik-sakshi
