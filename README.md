✈️ Flight Deal Tracker  
A Python project that tracks cheap flight deals and sends email alerts when prices drop below a set threshold.

---

🚀 How It Works  
- Fetches destination data from a Google Sheet (via Sheety API)  
- Uses the Tequila Kiwi API to search for flight deals from a specified origin city  
- Compares current prices with your minimum prices from the sheet  
- Sends an email alert using SMTP if a cheaper deal is found  

---

📁 Project Files  
- `main.py` – Orchestrates the complete workflow  
- `data_manager.py` – Handles reading/writing destination and user data via the Sheety API  
- `flight_search.py` – Connects with the Tequila Kiwi API to search for flights  
- `flight_data.py` – Structures the flight data for easy use  
- `notification_manager.py` – Sends email notifications to users  
- `.env` – Stores API keys and credentials (not committed to version control)  

---

🛠️ Setup Instructions  
1. Clone the repository:  
```bash
git clone https://github.com/PTharun007/flight-deal-tracker.git
cd flight-deal-tracker
