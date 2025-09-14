# Opticlass – Phase 2 (Extended Features)

**Opticlass Phase 2** builds on the MVP, adding advanced engagement tools, parental access, basic AI predictions, and online resources.  

---

## New Features in Phase 2
- **AI Predictions:** Simple exam outcome predictions based on student performance.  
- **Attendance & Engagement Tracking:** Track student presence and participation.  
- **Parent Portal (Basic):** View student grades, attendance, and progress.  
- **Resource Management:** Teachers upload lessons, assignments, and e-learning materials.  
- **Basic Online Payments:** Integrate payment gateway for school fees (optional).  

---

## Tech Stack Updates
- Payment integration: Stripe / Paystack / Flutterwave  
- Attendance tracking module  
- AI module for basic predictive analytics  

---

## Installation
```bash
# Clone the repository
git clone https://github.com/Neza360/Opticlass.git
cd Opticlass

# Switch to Phase 2 branch if applicable
git checkout docs  # or your Phase 2 branch/folder

# Install backend dependencies
pip install -r requirements.txt

# Install frontend dependencies
cd opticlass-ui-ux
npm install
npm run dev
