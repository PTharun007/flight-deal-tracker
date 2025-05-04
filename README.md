# ✈️ Flight Deal Tracker

A Python project that tracks cheap flight deals and sends **email alerts** when the price drops below a set threshold.

## 🚀 How It Works

1. Fetches destination and user data from a Google Sheet using the **Sheety API**.
2. Uses the **Amadeus API** to search for flight deals from a specified origin city.
3. Compares current flight prices against user-defined minimum price thresholds.
4. Sends an **automated email** via SMTP if a cheaper flight is found.

## 📁 Project Files

- `main.py`: Orchestrates the complete workflow.
- `data_manager.py`: Reads/writes destination and user data using the Sheety API.
- `flight_search.py`: Handles flight search requests via the Amadeus API.
- `flight_data.py`: Structures and formats flight information.
- `notification_manager.py`: Sends email notifications to users.
- `.env`: Stores API keys and credentials (never commit this file).
- `requirements.txt`: Lists project dependencies.

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/PTharun007/flight-deal-tracker.git
cd flight-deal-tracker
