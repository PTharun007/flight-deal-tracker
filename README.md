# ✈️ Flight Deal Tracker

A Python project that tracks cheap flight deals and sends **email alerts** when the price drops below a set threshold.

## 🚀 How It Works

1. Fetches destination data from a Google Sheet (via Sheety API).
2. Uses the **Tequila Kiwi API** to search for flight deals from a set origin city.
3. Compares current prices with your minimum price from the sheet.
4. Sends an **email alert** using SMTP if a cheaper deal is found.

## 📁 Project Files

- `main.py`: Orchestrates the complete workflow.
- `data_manager.py`: Handles reading/writing destination and user data via the Sheety API.
- `flight_search.py`: Communicates with the Tequila Kiwi API to find flight deals.
- `flight_data.py`: Structures the flight data for easy access.
- `notification_manager.py`: Sends email notifications to users.
- `.env`: Stores API keys and credentials (never commit this file).

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/PTharun007/flight-deal-tracker.git
cd flight-deal-tracker

